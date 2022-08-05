# cloudformation-challenge3

First Try:
Use the infrastructure we created earlier to build and deploy EC2 Instance, VPC, Private Subnet & IAM Role and InstanceProfile,

The IAM Role to allow EC2 Session Manager to access our server. 
An InstanceProfile will allow passing the IAM role to our server.

Second Try:
Export VPCID & Private Subnet from challenge2-stack FILES AND Import VPCID & PRIVATE-SUBNET to challenge3-stack files.

We create Bash Script to run command creation of stacks on AWS CloudFormation.

run    $./(NAME-OF-BASH SCRIPT)    NameOfStack    File.yml    File.json
 
 ex: 
        $./create.sh challenge2-stack challenge2-network.yml challenge2-networkParameters.json

