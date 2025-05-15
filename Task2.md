# Terraform and Cloud: create the infrastructure to host your container.

1. Prerequisites
AWS account
IAM user with programmatic access (set via AWS CLI or env vars)
Terraform CLI installed
Docker image pushed to DockerHub

2. Configure AWS Credentials
   aws configure
   Or set env variables:
   export AWS_ACCESS_KEY_ID=your-key-id
   export AWS_SECRET_ACCESS_KEY=your-secret
   export AWS_DEFAULT_REGION=ap-south-1

3. Initialize Terraform
   terraform init

4. Preview the Changes
   terraform plan

5. Deploy the Infrastructure
   terraform apply

Access the Service
curl http://simple-time-lb.amazonaws.com
