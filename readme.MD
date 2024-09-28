## terraform-aws-ec2

## Arguments

ami_id - (Mandatory), User must provide AMI ID. This is the string format
instance_-type - (optional), default is t3.micro 
security_group_ids - (Mandatory), user must provide list of SG ID 

## outputs

public_ip - Public IP of the instance created
private_ip - Private IP of the instance created
instance_id - Instance ID of the instance created
