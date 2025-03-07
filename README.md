# Serverless Newsletter System

![serverless_newsletter_architecture drawio (1)](https://github.com/user-attachments/assets/a3cf419b-99f2-438d-94c0-555e95d4dcc0)

A serverless newsletter system built with AWS Lambda, API Gateway, S3, DynamoDB, SES, and IAM for email automation and storage.

## Features

* User subscription management
* Email automation with AWS SES
* Serverless backend using AWS Lambda and API Gateway
* Data storage with DynamoDB
* Secure access control with IAM
* Static asset storage in S3

## Architecture

1. **API Gateway** - Handles incoming HTTP requests.
2. **Lambda Functions** - Processes user subscriptions and email sending.
3. **DynamoDB** - Stores subscriber details.
4. **SES (Simple Email Service)** - Sends newsletters to subscribers.
5. **S3** - Stores static assets or email templates.
6. **IAM** - Manages secure access control for AWS services.

## Setup & Deployment

### Prerequisites

* AWS account
* AWS CLI installed and configured
* Node.js installed
* Serverless Framework (optional for easier deployment)
