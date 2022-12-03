Author:
    yusyamas (42Tokyo C Piscine 2022/10 Fail)

git url:
  git@vogsphere-v2.42tokyo.jp:vogsphere/intra-uuid-60a7ff0f-6ad7-4369-9cf9-42bd3a25803c-4473188-yusyamas

試験結果:
  norm errorで0pts
  コマンドライン引数が3でなかった場合に、エラーフラグを立てず、x,yを初期化していなかったため
  エラー処理がなされず最適化によって適当に決められたx,yがrush0X.cで走ってしまう事故が発生
