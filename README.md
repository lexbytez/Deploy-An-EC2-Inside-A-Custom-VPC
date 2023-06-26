# Deploy-An-EC2-Inside-A-Custom-VPC
Project Description So, let's say you have a cloud management team and they are in charge of deploying, you deploy an ec2 inside a vpc just for your team and you are to add the ec2 inside a public subnet making it accessible publicly.
Step One

Go to your AWS console and navigate to VPC

Create a VPC ,use the advanced VPC and more option(options allows to create Subnets and route table automatically linked to the VPC)

Once created edit your public subnet and enable auto assign public IPV4 address option

Navigate to internet gateways create and add a gataeway and attach to your VPC

Navigate to security groups, create a new security group for your VPC and edit Inbound rules on it
![1](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/ede2e13a-bf37-46ad-bf7c-fcc4ce627143)
![2](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/6ec7d688-b17e-4b0a-b68f-e59989c71574)
![3](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/9f3802da-05f2-45ce-97d5-4a3047550a36)
![4](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/0081fcf0-0fa7-4c54-a1e8-bdec148c2507)
![5](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/b2afd394-bd53-49d9-9221-a4daf240bc6f)
Step Two

Navigate to your EC2 Console and create an Instance, during creating selection edit network option
choose and attach your VPC, attach Subnet, select security group, scroll down to use data and paste data for project website
![11](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/5bd76793-a064-4765-9fe7-a80e202fdce8)
![22](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/d6f6b5af-b858-4edc-8a81-1ff1c57687bd)

once done connect to your instance, Website is up and running
![33](https://github.com/lexbytez/Deploy-An-EC2-Inside-A-Custom-VPC/assets/128375535/fefe9bbd-fd6e-4415-aef8-08cea3da5cf9)


