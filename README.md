# QiitaOrgWatcher

指定のQiita Organizationに投稿を検知し、Slackに通知します

# Configurations

| NAME               | REQUIRED | TYPE               | NOTES                          |
|--------------------|----------|--------------------|--------------------------------|
| QIITA_TOKEN        | ○        | STRING             | Qiita access token             |
| QIITA_ORGANIZATION | ○        | STRING             | Qiita Organization ID          |
| CREATED            | ○        | STRING(YYYY-MM-DD) | Created date for qiita article |
| SLACK_TOKEN        | ○        | STRING             | Slack access token             |
| SLACK_CHANNEL      | ○        | STRING             | Slack chanell                  |

# Quick Start

1. generate watcher access token
  * https://qiita.com/settings/applications
2. run application
```
$ <set envioromental variables>
$ export GO111MODULE=on
$ go build
$ go run
```

# Deploy Google Cloud Function



