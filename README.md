# Cloud-Computing-3031-Ex-1
**Description:**<br />
The system is fully serverless and deployed by cloud formation template and includes an API Gateway that calls a lambda function, that uses DynamoDB to store the parking data.

**To implement using aws CLI:**<br />

aws cloudformation create-stack --stack-name cloud-computing-3031-ex1-stack --template-body file://cloudComputing3031Ex1-stack.yaml --capabilities CAPABILITY_NAMED_IAM
