# demo.aws-vpc-public-private-dual-ec2

---

This project creates a new VPC with public and private subnets, routing, and two EC2 nodes. 

The project is inspired by the following hands-on lab, from ACloudGuru:
![img_3.png](img_3.png)

The following resources are created, INCLUDING the custom AWS Resource Explorer view:
![aws_resourceexplorer.png](aws_resourceexplorer.png)

The project deploys from scratch in less than one minute:
![terminal-output-create.png](terminal-output-create.png)

And can be completely destroyed in about the same:
![terminal-output-destroy.png](terminal-output-destroy.png)

### Resources created:

- Resource Explorer View
- Networking
  - VPC
  - Public Subnet
  - Private Subnet
  - VPC Internet Gateway
  - Route Table
- Compute
  - Key Pairs
  - Security Groups
- Compute Instances
  - t3.micro EC2 in public subnet
  - t3.micro EC2 in private subnet
