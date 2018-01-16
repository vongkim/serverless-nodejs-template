# A serverless AWS project
[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)

A serverless AWS project. The service is running on AWS using [Serverless Framework](https://github.com/serverless/serverless).


# Usage

Both `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` must be exported as environment variables as these are required by the AWS CLI.

## Setup
| **Step** | **Command** |**Description**|
|---|-------|------|
|  1. | `npm install -g serverless` | Install required global node packages  |

## Development
| **Command** |**Description**|
|------|------|

Examples:


## Deployment
The deployment command supports the following paramters:

TODO


# Tips & Tricks

### `help` command
Just use it on anything:

	sls  help
or

	sls <command> --help

### `deploy function` command
Deploy only one function:

	sls deploy function -f <function-name>

### `logs` command
Tail the logs of a function:

	sls logs -f <function-name> -t

### `info` command
Information about the service (stage, region, endpoints, functions):

	sls info

### `invoke` command
Run a specific function with a provided input and get the logs

	sls invoke -f <function-name> -p event.json -l
