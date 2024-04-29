# Serverless-application-model - introduction
AWS SAM (Serverless Application Model) là một open-source framework giúp Developer dễ dàng build và deploy serverless applications trên AWS

Nó sử dụng AWS CloudFormation để định nghĩa infrastructure và resource cho serverless application ví dụ như Lambda Function, API Gateway, DynamoDB

SAM hỗ trợ nhiều ngôn ngữ lập trình Node. js, Java, Python, .NET and Go

SAM cung cấp môi trường test và debug ở local cho phép Developer có thể test code trước khi deploy lên AWS

Nó cũng cung cấp pre-built templates cho những common serverless application architectures, giúp chúng ta dễ dầng bắt đầu build một serverless applications.

Tích hợp với  AWS CodePipeline cho CI/CD

Cung cấp command-line interface (CLI) và AWS Toolkit for Visual Studio Code

Đây là công cụ free

Một số command line:
sam init - cung cấp các option để khởi tạo new serverless application
sam build - chuẩn bị serverless application cho quy trình deployment tiếp theo như  local testing hoặc deploying to the AWS Cloud.
sam deploy - command to deploy your serverless application to the AWS Cloud.
sam delete - command cho phép xóa resource của serverless application bằng cách xóa Cloudformation stack
URL: 
https://blog.cloudmentor.pro/blog/aws-dva/create-build-and-deploy-a-sample-hello-world-app-using-aws-sam#1-create-an-aws-cloud9-development-environment
