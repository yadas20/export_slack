# export_slack
エクスポート機能を使用せずにSlackAPIを使用してメッセージ内容を取り出す

### できること
Slackの特定のチャンネルを対象に、メッセージ履歴を取得してCSVファイルに出力

※Slackのエクスポート機能を使わない方法

### 出力内容
>1. メッセージタイプ(メッセージ or メッセージへのスレッド返信)
>2. 投稿者
>3. 投稿時刻
>4. メッセージ内容

## Requirement
- Python 3.9

- SlackAPI

  > token取得に使用するスコープ
    >  - channels:history
    >  - channels:read
    > - groups:history
    > - im:history
    > - mpim:history
    > - users:read

