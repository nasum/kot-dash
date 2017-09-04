## KOT DASH

キングオブタイムを Amazon Dash Button で打刻するスクリプト

## 実行方法

### 設定

`.env` に環境変数を記述。

* `START_DASH_MAC_ADDRESS` 業務開始に使用する Dash Button の MAC アドレス
* `STOP_DASH_MAC_ADDRESS` 業務終了に使用する Dash Button の MAC アドレス
* `KOT_TOKEN` King of Time のトークン
* `USER_KEY` 対象ユーザのキー

### 実行

```bash
$ node index.js
```
