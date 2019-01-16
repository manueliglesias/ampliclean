# ampliclean
Command line tool to clean aws resources. 
This command line tool is intended to be only used to clean up resources in aws account that are only for dev and test purposely. Do NOT use it on production aws account. 

## Install the CLI
This tool is not published to the npm. 
Clone the repo and run `npm link` to use it. 

## Commands Summary

The current set of commands supported by the ampliclean CLI are

| Command              | Description |
| --- | --- |
| ampliclean cloudformation | removes all cloudformation stacks in your account|
| ampliclean pinpoint | removes all pinpoint projects in your account|
| ampliclean s3 | removes all s3 buckets in your account|
| ampliclean configure | configures the cli |
| ampliclean help [cmd] | Displays help for [cmd] |
