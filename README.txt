Mind Series アイコン修正版

このZIPは Mind Series のホーム画面アイコンだけを直すためのファイルです。
Dog Mind / Human Mind のアイコンファイルは含めていません。

GitHub の Mind Series リポジトリの index.html と同じ階層へ、
ZIP内のPNGファイルをアップロードしてください。

index.html の <head> 内に次の指定があることを確認してください。

<link rel="apple-touch-icon" sizes="180x180" href="./apple-touch-icon.png?v=2">
<link rel="icon" type="image/png" sizes="192x192" href="./favicon-192.png?v=2">
<link rel="icon" type="image/png" sizes="512x512" href="./favicon-512.png?v=2">
<link rel="manifest" href="./manifest.webmanifest?v=2">

iPhoneは古いホーム画面アイコンをキャッシュします。
GitHub Pages更新後、今ある灰色の「M」のMind Seriesだけをホーム画面から削除し、
SafariでMind Seriesを開き直して「ホーム画面に追加」してください。
Dog Mind / Human Mind は削除不要です。
