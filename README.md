## Table of contents

- Introduction
- Deployment instructions

## Introduction
This pattern demonstrates a low code way to send DynamoDB stream records to EventBridge using EventBridge Pipes.

This project helps establish a demo to allow developers to test the EventBridge Pipes capability. 

## Deployment instructions
1. Install sam cli on your machine
    ```
    https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html
    ```
1. Do a git clone of the repository
    ```
    git clone git@github.com:rahul-grover/eb-pipes.git
    ```
1. Go to the cloned directory 
    ```
    cd eb-pipes
    ```
1. Initialize and build 
    ```
    sam build
    ```
1. Deploy 
    ```
    sam deploy --profile <change_to_your_profile> --region <change_region> --stack-name <provide_stack_name> --capabilities CAPABILITY_IAM
    ```
