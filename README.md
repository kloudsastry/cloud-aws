# cloud-aws
## Cloud Foundation
- Greenfield Accounts
- Brownfield Accounts
- Landing Zone
  - AWS Organizations
  - AWS Control Tower Factory for Terraform
    - Master billing Account
    - Security Account
    - Log archive Account
    - AWS regions supported
    - Enabling Cloud Trail audit
    - AWS Customizations
  - SSO Integration
## Networking
- VPC
  - No. of VPC's in AWS account
- Subnets
  - Design
    - Red subnets
    - Yellow subnets
    - Container subnets
    - Green subnets
- Routing
- Transit Gateway
- Direct connect
## Security
- Cloud Custodian
- AWS GuardDuty
- SCP Policies
- IAM Roles
  - Cross Account Roles
  - Service Link Roles
  - IAM Users
## Infrastructure As Code
- Terraform
  - Why terragrunt?
  - Provisioning
    - Git branching
    - Infrastructure Governance
    - State file management
    - User data management
  - LCM management using terraform
  - Avoid Drift
## Services
- EC2
  - Spot instances
  - Reserved Instances
  - On-Demand Instances
- S3
  - Bucket Encryption
- RDS
## AMI Engineering
- AMI Build Process
  - Implementing Packer
  - Integrating Ansible with Packer
  - Updating Parameter store with AMI ID
  - Sharing AMI ID's to Multiple Accounts
- Server Hardening - CIS Commandments
  - ARM Platform
    - RedHat
    - Amzn Linux 2
    - Ubuntu
    - Windows 2016
    - Windows 2019
    - EKS Optimized
    - ECS Optimized
  - x86 Platform
    - RedHat
    - Amzn Linux 2
    - Ubuntu
    - Windows 2016
    - Windows 2019
    - EKS Optimized
    - ECS Optimized
  - Supported Marketplace AMI's
- AMI Rollout
  - Current AMI Info
  - Previous AMI Info
  - Updating ASG with latest AMI Info
## Kubernetes
## Cloud Governance
## FinOps
- AWS Cost Management
- CUR Reports
- Tagging
## Cloud Operations
### Backup
- EC2 Snapshots
- RDS Backups
### Monitoring
### Automations
## Cloud Migration

