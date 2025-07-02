# Ansible AWS VM Monitoring

This Ansible playbook helps you monitor EC2 instances on AWS by tracking metrics like CPU, memory, disk, and network usage. It supports sending alerts when thresholds are exceeded and allows automated, real-time monitoring of your AWS virtual machines.

**Note--- will soon complete this repo, busy atm**

## Features

- **Monitor EC2 instances**: Check the health and resource usage of your EC2 instances.
- **Customizable thresholds**: Set thresholds for CPU, memory, disk, and network usage.
- **Alerts**: Send email alerts when an instance exceeds the defined resource thresholds.
- **Automation**: Run monitoring tasks on a scheduled basis via cron jobs or other schedulers.
  
## Prerequisites

Before using this playbook, you will need:

- **Ansible** (installed via `pip install ansible`)
- **AWS CLI** (configured with your AWS account credentials)
- **Boto3** and **botocore** Python libraries (`pip install boto3 botocore`)
- **IAM Permissions** for EC2 and CloudWatch metrics (e.g., `ec2:DescribeInstances`, `cloudwatch:GetMetricData`)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/saahil-ops/ansible-vm-monitoring.git
cd ansible-vm-monitoring
