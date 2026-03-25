# AWS Serverless Task API

A serverless task management API built with AWS Lambda, API Gateway, DynamoDB, and Cognito.

## Features
- User authentication with Amazon Cognito
- REST API with authenticated CRUD operations
- Serverless compute with AWS Lambda
- NoSQL task storage with DynamoDB
- Monitoring with CloudWatch

## Architecture
Client -> API Gateway -> Lambda -> DynamoDB
                    -> Cognito for Auth

## Tech Stack
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- Amazon Cognito
- AWS SAM
- Python

## Goals
This project is designed as a production-style cloud portfolio project to demonstrate:
- serverless architecture
- API security
- AWS integration
- observability
- infrastructure-aware development
