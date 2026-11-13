# list

旅行の持ち物チェックリスト「持ち物リスト」。https://list.minervalab.jp/ で公開。

- `index.html` … アプリ本体（1ファイル完結、SortableJS 1.15.7 を埋め込み）
- `manifest.json` / `icons/` … ホーム画面に追加したときに全画面で開くための設定とアイコン
- `sw.js` … オフラインでも開けるようにする Service Worker
- データはその端末のブラウザ（localStorage `packlist.v1`）に保存。編集モード下部からバックアップの書き出し／読み込みができる
