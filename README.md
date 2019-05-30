# leran_aws

## AWS Lambda

- 関数名は変更できない。
  - https://teratail.com/questions/62275
- レイヤーとしてアップロードするファイルは、python/hoge.py などとなっている必要がある。
  - 罠。
- cronはドキュメントを見ながら描くべし。
  - https://docs.aws.amazon.com/ja_jp/AmazonCloudWatch/latest/events/ScheduledEvents.html
- 処理はハンドラの中に書くこと。（ただコードを書けば良いというわけではないので注意）
- モジュールの作成は下記URLを参照。
  - https://kiito.hatenablog.com/entry/2017/05/06/145424
  - https://qiita.com/hihats/items/56005088f0f2018143cf#_reference-82a3edf39357ed517d2f
    - 3.6環境。3.7のdockerイメージがあるかチェック。そもそもローカル環境で作れるかもチェック。
- 環境変数も設定可能。
