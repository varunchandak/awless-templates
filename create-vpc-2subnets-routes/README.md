This will create/do the following:

* 1 VPC
* 2 Public Subnets
* 2 Private Subnets
* 1 Public Route
* 1 Private Route
* 1 Elastic IP (for NAT Gateway)
* 1 NAT Gateway
* 1 Internet Gateway (IGW)
* 1 Instance
* 1 Security Group (with ping for specific CIDR)
* Attach elastic IP with the NAT Gateway
* Attach IGW with the public route table
* Attach NAT Gateway with the private route table
