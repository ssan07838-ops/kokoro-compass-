# こころのコンパス — GitHub Pages 公開手順

1. GitHub で新しいリポジトリを作成（例: kokoro-compass、Public）
2. 「Add file → Upload files」で、このフォルダの全ファイルをアップロードして Commit
   （index.html / manifest.webmanifest / icon.svg / icon-180.png / icon-192.png / icon-512.png）
3. Settings → Pages → Branch を「main」「/ (root)」にして Save
4. 1〜2分後、 https://<ユーザー名>.github.io/kokoro-compass/ で公開されます
5. 更新するときは index.html を同じ名前で上書きアップロード → 同じURLに反映

- 団体の説明文は index.html 内の `ORG_NOTE` を書き換えると変更できます。
- スマホで開いて「ホーム画面に追加」すると、アプリのように起動できます。
- 回答はどこにも送信・保存されません（サーバー不要）。
- 性格テスト部分は TIPI-J（小塩・阿部・カトローニ, 2012）を原文どおり使用しています。質問文・選択肢・採点式は変更しないでください。

## 共有用QRコード（右上の「？」）
- GitHub Pagesで公開すると、QRコードとリンクは自動でそのページのURLになります。
- 確実にしたい場合は、index.html 内の `SHARE_URL = null;` を `SHARE_URL = 'https://<ユーザー名>.github.io/kokoro-compass/';` に書き換えてください。
- QRコードの作成には Kazuhiko Arase 氏の QRCode for JavaScript（MITライセンス）を同梱しています。
