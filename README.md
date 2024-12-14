# CloudFormation S3 Bucket Template

This repository contains an AWS CloudFormation template to create an S3 bucket.

## Template Overview

The CloudFormation template defines the creation of an S3 bucket with the following specifications:

- Bucket name: `myuniquebucketname` (Ensure this name is globally unique for your account)
- The bucket name is in lowercase and contains no numbers, following AWS naming conventions.

## Prerequisites

- An active AWS account.
- AWS CLI or AWS Management Console access to deploy the CloudFormation stack.
- The bucket name specified must be globally unique.

## How to Use the Template

1. Save the YAML content to a file named `s3-bucket.yaml`.
   
2. Deploy the CloudFormation stack using the AWS CLI:

   ```bash
   aws cloudformation create-stack --stack-name MyS3BucketStack --template-body file://s3-bucket.yaml
