# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template



Run AWS Instance:
/Users/admin/Downloads/linuxkey.pem


Run the Linux:
ssh -i "linuxkey.pem" ec2-user@ec2-52-21-109-111.compute-1.amazonaws.com

Transfer file from Local to Remote:

sftp -i "linuxkey.pem" ec2-user@ec2-52-21-109-111.compute-1.amazonaws.com

put <local path> <remote path>



Jenkin URl: http://52.21.109.111:8080