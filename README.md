# DC_PerformanceVisualizer

企業型確定拠出年金(DC)の銘柄ごとのパフォーマンスを可視化するツール

## 作った経緯

公式サイトの機能では銘柄ごとのパフォーマンスが見れなかったため

## 構成

当方の環境では以下構成で構築

- PowerAutomateDesktopでサイトをスクレイピングし、結果をjson形式で保存
- 本ツールで当jsonデータを読み込み、グラフ化

## 依存関係

- Grid.js
- Chart.js

## LICENSE

[License](/LICENSE "License")