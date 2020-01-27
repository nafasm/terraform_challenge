# challeng
Public challenge
There are 3 files have been attached here, and their details are given below 

Terraform_configuration

#######################

Terraform_configuration file, has all the hcl codes to create the following 
        1. A new vpc named  vpc_devop
        2. A new public subnet named "sub_public_devops"
        3. A new security group named "sg_devops" which allows access from "0.0.0.0/0" for SSH(22) and HTTP(80)
        4. A new EC2 key pair named "kp_devops"
        5. A new EC2 instance of type t2.micro of any linux distro named "ec2_devops", with security group "sg_devops", and accessible by              SSH with "kp_devops"
        6. assign a static public IP to "ec2_devops", and expose this public IP as terraform output
        7. Create route for vpc (vpc_devop) and associate the route to subnet sub_public_devops

terrafrom plan

##############

Terraform plan file has both the terraform plan and terraform apply output of the terraform configuration. 
ssh_screenshot.PNG

##################

This screenshot shows, EC2 instance ec2_devops has been accessible from the internet using key pair kp_devops
