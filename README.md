## 下準備

```sh
$ aws s3 mb s3:massat.jp
$ aws elasticbeanstalk create-application --application-name=massat.jp
$ aws elasticbeanstalk list-available-solution-stacks | grep Docker
$ aws elasticbeanstalk create-environment --application-name=massat.jp --environment-name=massatjp --solution-stack-name="64bit Amazon Linux 2016.03 v2.1.3 running Docker 1.11.1"
```
