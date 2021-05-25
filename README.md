# sample_terraform_tests
Repo for sample lauch configuration for EC2 instances using AWS provider
To run it run:
$ export AWS_ACCESS_KEY_ID="<>"
$ export AWS_SECRET_ACCESS_KEY="<>"
$ export AWS_DEFAULT_REGION="<>"
$ terraform plan
$ terraform apply

# Common terraform commands
terraform –version
terraform init (create resources)
terraform show
terraform plan (see what was added or removed without doing it)
terraform apply
terraform apply -var ‘access_key=foo’ -var ‘secret_key=bar’

# terraform terminology
Providers and resources: main.tf
Implicit/explicit dependencies
Provisioner: execute code in resource
Variables in input.tf
Output variables with dependencies
Terraform lifecycle: create_before_destroy
