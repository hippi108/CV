# CV

GitHub Pagesで公開するCVサイトです。

## ファイル構成

- `index.html`: CVの本文
- `assets/css/style.css`: 色、余白、レイアウト、スマートフォン向けの設定
- `assets/images/`: 今後追加する画像

画像は `./assets/images/photo.jpg` のような相対パスで参照します。
JavaScriptが必要になったら `assets/js/main.js` を作成し、HTMLから `<script src="./assets/js/main.js" defer></script>` で読み込みます。

## 確認

このフォルダで `python3 -m http.server 8000` を実行し、ブラウザで http://localhost:8000 を開きます。

## GitHubへの更新

```bash
git add index.html assets/ README.md
git commit -m "Update CV"
git push
```

GitHub Pagesは Settings → Pages で `main` / `/ (root)` を公開元に設定します。
