VPC
Internet Gateway
Subnet
Route table
Security Group and then,
EC2 instance definition
Install Apache web server 
Steps to run Terraform
terraform init
terraform plan -var-file=aws.tfvars
terraform apply -var-file=aws.tfvars -auto-approve
Once the terrform apply completed successfully it will show the public ipaddress of the apache server as output
aws_instance.web: Creation complete after 33s [id=i-07f19000878a6ec11]

Apply complete! Resources: 7 added, 0 changed, 0 destroyed.

Outputs:

web_instance_ip = "34.220.248.140"
Encrypt the disk
Logs sent to cloud watch 
Versioning, audit trails are enabled on file/object stores
$ terraform import aws_cloudwatch_log_subscription_filter.test_lambdafunction_logfilter /aws/lambda/example_lambda_name|test_lambdafunction_logfilter
 