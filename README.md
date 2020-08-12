### Important Terninology
- VPC - Virtual Private Cloud in AWS to launch computing resources.
- IGW - Internet gateway, attached to the VPC and allows internet into the VPC via route table.
- Subnet - Internal networking
- NACLs - Network Access Control list, this is an optional layer of security for your machine. (A firewall at the level of a subnet)
- Route Tables - Contains a set of rules, called routes that determine where network traffic from a subnet or gateway is directed.
- SG - Security Group / Firewall
- EC2 - Amazon Elastic Compute Cloud

### What is a VPC?

- a vpc is a virtual private cloud, where can define a virtual network to launch aws resoucres in
- tier 2 means seperating servers into app and db for example
- this creates a multi tier architecture and is therefore more robust

### What is a internet gateway? IGW

An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses. An internet gateway supports IPv4 and IPv6 traffic.


### What is a Subnet?

- a segment of a VPC’s IP address range where you can place groups of isolated resources
- can be used to limit ips used

### What is a route table?

A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet or gateway is directed.

### What is Network ACL?

- in NACL you Need to set outbound rules. By default, outbound traffic is denied

- Rules number matter, and you can deny IP as well as allow

