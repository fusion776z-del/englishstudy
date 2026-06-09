# EIKEN JS Package

`index.html` から `eiken_pages.js` を読み込み、`eiken_loader.html?page=...` 経由で `pages/*.js` に埋め込んだHTMLを表示します。

含まれるページ: 4,5級 / 3級 / 準2級 / 2級 / 準1級

再生成する場合は、`source_html` 内の元HTMLをトップ階層へコピーしてから `node build-eiken-js.mjs` を実行してください。
