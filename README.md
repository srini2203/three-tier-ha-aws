##  Production-Style Three-Tier AWS Architecture

> A production-inspired highly available AWS infrastructure built using Infrastructure as Code (CloudFormation), following AWS Well-Architected principles for security, scalability, monitoring, and reliability.


##  Project Overview

This project demonstrates the design and deployment of a highly available three-tier architecture on AWS.

The infrastructure incorporates networking, compute, security, monitoring, auditing, and compliance services commonly used in production cloud environments.

---

##  Architecture

> *(Architecture diagram will be added here)*


##  AWS Services Used

### Networking
- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs

### Compute
- Amazon EC2
- Launch Templates
- Auto Scaling Group
- Application Load Balancer

### Security
- IAM
- IAM Roles
- AWS WAF
- AWS KMS

### Monitoring & Auditing
- Amazon CloudWatch
- Amazon SNS
- AWS CloudTrail
- AWS Config

### Infrastructure as Code
- AWS CloudFormation


##  Security Features

- Private application infrastructure
- Security Groups implementing least privilege
- IAM Roles (no hardcoded credentials)
- KMS encryption
- AWS WAF protection
- CloudTrail auditing
- AWS Config compliance monitoring


##  Monitoring

- CloudWatch Metrics
- CloudWatch Alarms
- SNS Notifications
- Health Checks
- ALB Monitoring



##  Infrastructure as Code

Infrastructure is provisioned using AWS CloudFormation templates.

```
cloudformation/
```


##  Project Screenshots

Screenshots demonstrating each deployment stage are available in the `screenshots/` directory.



##  Documentation

Detailed documentation is available in the `docs/` directory.

- Deployment Guide
- Design Decisions
- Security Design
- Monitoring
- Cost Analysis
- Interview Guide



##  Current Status

Project Version: **v0.1.0**

Status:

-  Networking
-  Compute
-  Security
-  Documentation in progress
-  Architecture diagram in progress



##  Future Improvements

- HTTPS using ACM
- Route53
- CloudFront
- CI/CD with GitHub Actions
- CloudFormation modularization
- Terraform implementation
- ECS migration
  

##  Author

**V. Srinivasan**

AWS Certified Cloud Practitioner

Aspiring Cloud Security Engineer
