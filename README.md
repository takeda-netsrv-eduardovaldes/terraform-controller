# Provision Terraform - Infrastructure As Code (IaC)
GitHub Actions - Provision Terraform - Infrastructure As Code (IaC)

![GitHub Actions - Terraform Controller](https://github.com/emvaldes/terraform-controller/workflows/GitHub%20Actions%20-%20Terraform%20Controller/badge.svg)

GitHub Secrets (Required):

```
AWS_ACCESS_KEY_ID           Service-Account AWS Access Key-Id (e.g.: AKIA2...VT7DU).
AWS_DEFAULT_ACCOUNT         The AWS Account number (e.g.: 123456789012).
AWS_DEFAULT_PROFILE         The AWS Credentials Default User (e.g.: default).
AWS_DEFAULT_REGION          The AWS Default Region (e.g.: us-east-1)
AWS_SECRET_ACCESS_KEY       Service-Account AWS Secret Access Key (e.g.: zBqDUNyQ0G...IbVyamSCpe)
BACKUP_TERRAFORM            Enable|Disable (true|false) backing-up terraform plan/state
DEPLOY_TERRAFORM            Enable|Disable (true|false) deploying terraform infrastructure
DESTROY_TERRAFORM           Enable|Disable (true|false) destroying terraform infrastructure
DEVOPS_ACCESS_ROLE          Defines the AWS IAM Role: 'DevOps--Custom-Access.Role'
DEVOPS_ACCOUNT_NAME         A placeholder for the Deployment Service Account's name (devops).
PRIVATE_KEYPAIR_FILE        Terraform AWS KeyPair (location: ~/.ssh/id_rsa).
PRIVATE_KEYPAIR_NAME        Terraform AWS KeyPair (e.g.: devops).
PRIVATE_KEYPAIR_SECRET      Terraform AWS KeyPair (PEM, Private file)
PROVISION_TERRAFORM         Enable|Disable (true|false) the provisioning of the terraform-toolset
TARGET_WORKSPACE            Identifies which is your default (current) environment
```
