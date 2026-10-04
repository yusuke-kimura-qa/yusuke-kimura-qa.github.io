# yusuke-kimura-qa.github.io

Yusuke Kimura のポートフォリオサイト。GitHub Pages で公開します。

- ビルド不要の HTML + CSS のみ（JavaScript・Webフォントなし）
- ライト / ダークモードは OS の設定に自動で合わせます

## ファイル構成

| ファイル | 内容 |
|---|---|
| `index.html` | トップページ（Works / Approach / About） |
| `works/mimica.html` | Mimica のケーススタディ |
| `style.css` | 全ページ共通のスタイル |
| `404.html` | 存在しないURLを開いたときのページ |

## 作品を追加するとき

1. `index.html` の `#works` セクションに `<article class="card">` を1つ追加
2. 詳しく見せたい場合は `works/` に新しいページを作る（`works/mimica.html` をコピー）
3. 画像は `images/` に置き、`<img loading="lazy" width="…" height="…">` で読み込む

## ローカルで確認する

`index.html` をブラウザで開くだけで確認できます。
