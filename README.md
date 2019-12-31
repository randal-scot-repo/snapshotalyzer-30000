# snapshotalyzer-30000

Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shottypy <command> <subcommand> <--project=PROJECT>"`

*command* is list, start, or stop
*subcommand* - depends on command
*project* is optional
