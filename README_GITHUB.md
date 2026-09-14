# Galaxy Photo Shuffle – S26+ GitHub Build版

このフォルダをGitHubリポジトリへアップロードすると、GitHub ActionsでAPKをビルドできます。

## S26+での最短手順

1. GitHubで新しいリポジトリを作る。
2. このZIPを展開する。
3. 展開したファイルとフォルダをリポジトリのルートへアップロードする。
4. GitHubの「Actions」を開く。
5. 「Build Galaxy Photo Shuffle APK」を選ぶ。
6. 「Run workflow」を押す（mainへのpushでも自動実行）。
7. 成功したらWorkflow runを開く。
8. 「Artifacts」から `GalaxyPhotoShuffle-S26Plus-APK` をダウンロード。
9. ZIPを展開し、中の `app-debug.apk` をタップしてインストール。

## 注意

これはデバッグ署名APKです。Playストア公開用の署名済みリリースAPKではありません。
GitHub Actionsのビルド成果物には保存期限があります。
