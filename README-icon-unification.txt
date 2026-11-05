# クレドクエスト 正規アイコン一式

正規アイコンは、会社版サイトのPWA設定 `manifest.webmanifest` が現在参照している
`icons/kredo-quest-192.png` と同じフクロウ画像です。

- `kredo-quest-192.png`: サイトの現行アプリアイコン原本（192×192）
- `kredo-quest-512.png`: 同じ画像の512×512版（大きいアイコンが必要なサービス用）
- `kredo-quest-icon.svg`: 原本PNGを埋め込み、見た目を完全に合わせたSVG版
- `icon-head-snippet.html`: ブラウザタブ、ホーム画面、共有プレビューで同じ画像を使うためのheadタグ

既存の `icons/kredo-quest-192.png` はすでに正規アイコンです。
混在している盾デザインの `icons/kredo-quest-icon.svg` を同梱SVGで置き換え、
`icon-head-snippet.html` のタグを各HTMLの `<head>` に追加します。
