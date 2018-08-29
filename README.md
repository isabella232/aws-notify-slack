# AWS-Notify-Slack
Lambda function that format and forward a AWS event to slack

![alt text](https://github.com/TeliaSoneraNorge/aws-notify-slack/blob/master/media/warn.png)
![alt text](https://github.com/TeliaSoneraNorge/aws-notify-slack/blob/master/media/ok.png)

## Run unit tests 
$ make test

## Build binary 
$ make build

## Run function using sam local with snsEvent payload  
$ make run

## Environment Variables

|      Name     |     Required  |     Type      |   Description  |
| ------------- | ------------- | ------------- | -------------- |
| SLACK_HOOK    | Yes           | String        | Slack hook url |
| USERNAME      | No            | String        | Slack username |
| ICON          | No            | String        | Slack icon     |