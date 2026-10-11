# 社内課題対応状況 入力画面

Teams「経営ボード ＞ 一般」の `社内課題対応状況.xlsx` を
ブラウザから読み書きするための 1 ファイル SPA です。

- Microsoft Entra ID でサインイン（ECH テナント限定）
- Microsoft Graph の Excel API でセル単位に読み書き
- 書き込み可否は SharePoint 側の権限（経営ボードチームのメンバーシップ）で決まります

このページ自体に機密情報は含まれません。
サインインしない限り Excel の内容は一切読み込まれません。

設定は `index.html` 冒頭の `CONFIG` にまとまっています。
