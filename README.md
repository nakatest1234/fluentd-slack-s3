# fluentd-slack-s3

- 日本時間にした
- シークレットキー、クレデンシャル、IAMロールでconfig切り替えできないので、シークレットキー認証のみにしました
- s3.{env}.{app}.{logtype} のタグで送るとS3保存
- notice.{env}.{channel} のタグで送るとslackへ通知
- noticeのmatchで@type copyすれば複数へ通知できます
