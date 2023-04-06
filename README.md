# aws-event-driven-architecture

Uses events to decouple an application’s components

Sample usecase:
1. Event producer: AWS S3 bucket
2. Event ingestion: AWS SNS
3. Event stream: AWS SQS
4. Event consumer: AWS lambda

This repo contains SNS access policy, SQS access policy, SNS subscription filter policy and IAM lambda policies used in this implementation.
