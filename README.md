# PEGS

杭に輪ゴムを張る要領で文字の輪郭を作り、SVG で書き出すツール。

- 杭を立てて、ゴムを掛けて、輪郭を閉じる
- 杭ごとに太さ（半径）を変えられる
- ズームとパンで、大きなロゴも広い盤のまま作れる
- SVG / PNG / JSON で書き出し、盤はリンクにして共有できる

## 使う

`index.html` を開くだけ。ビルドも依存もなし（フォントだけ Google Fonts から読む）。

GitHub Pages を有効にすればそのまま公開できる（Settings → Pages → Deploy from a branch → `main` / root）。

## ファイル

| path | |
| --- | --- |
| `index.html` | 本体。これ一枚で動く |
| `aphex.json` | 盤のサンプル。アプリ内の LOAD から読み込む |
