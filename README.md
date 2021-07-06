The Distributed whitebaord system that can be shared between multiple users over the network and the Design consist of VPC(Virtual private cloud) where the  distributed whiteboard application is hosted .
Below is list of services used in private cloud system .
Region - eu-west-2(London)

1- VPC
2- public subnet in VPC
3- EC2 instance – launch in private subnet(t2.micro)
4- Auto scaling group and Elastic load balancers
5- Security groups for ec2 (inbound and outbound)
6- Storage memory EBS 
7- Route tables and Internet gateway for internet connectivity
8- Monitoring is ON for services (Cloud watch metrics)
9- For whiteboard application layer we do not need Database layer
10-For cost management we have Billing dashboard, AWS budgets , Cost and Usage reports etc.
11-Amazon Athena – analysing the logs

![alt text](https://github.com/ss1307-uol/whiteboard/blob/master/ICC-CW3.png?raw=true)
