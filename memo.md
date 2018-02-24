# github for unityの導入

1. https://github.com/github-for-unity/Unity/releases
ここからgithub用assetを落とす

1. 普通にproj作る

1. assetを実行するとunityのprojにassetがインスコされる

1. authしてshow windowからcommitしたりpublishしたりする


# mmdファイルをunity用にエクスポート

## mmdをインポート
1. 下メニューの[オブジェクトモード]の横のアイコンでテクスチャ(格子模様)を選択
1. 右メニューで[表示と編集を行うアクティブデータのタイプ]を選択
1. [ランプ]エリアで[ヘミ]を選択

## blenderでエクスポート
ファイル>外部データ でblendファイルに自動パック&絶対パス

設定で

* zが前方
* ランプ,カメラを外す(shift+クリック)
* パスモードは絶対パスにする

でエクスポートする

モデル1体につきassetフォルダを用意し、テクスチャファイルを全部配置>fbxを配置する

※もしくはimportするときにfbx+テクスチャファイル全部を同時にD&Dするとテクスチャが適用される

