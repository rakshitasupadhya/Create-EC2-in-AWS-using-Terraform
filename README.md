# Create-EC2-in-AWS-using-Terraform
Demonstration on creating a EC2 instance using Terraform

# Steps
1. Write a HCL code to launch EC2 instance. Refer main.tf for the code
2. Add subnet_id & AMI accordingly
3. Run Terraform init, terraform plan & terraform apply commands
![image](https://github.com/rakshitasupadhya/Create-EC2-in-AWS-using-Terraform/assets/107621546/c6a2f064-1e00-4577-b508-ac006803a3a4)
![image](https://github.com/rakshitasupadhya/Create-EC2-in-AWS-using-Terraform/assets/107621546/1d05c2a6-5b49-4f11-bafe-4bfea91da9b0)
![image](https://github.com/rakshitasupadhya/Create-EC2-in-AWS-using-Terraform/assets/107621546/290dd47f-3fb2-48b1-bc62-80e410f30004)
5. Open AWS console and verify if EC2 with tag name is created
<img width="803" alt="image" src="https://github.com/rakshitasupadhya/Create-EC2-in-AWS-using-Terraform/assets/107621546/0eacc770-2038-4c52-a5fb-1e232f9b70fc">
6. Execute terraform destroy command
![image](https://github.com/rakshitasupadhya/Create-EC2-in-AWS-using-Terraform/assets/107621546/c51e77ef-bc12-4601-8ff0-4941dc13acc8)

   
