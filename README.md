 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
The goal of this experiment is to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.
## Algorithm

### Step 1
**Login to AWS Management Console:**
1. Open the AWS Management Console.
2. Navigate to the **S3** service for bucket creation and **EC2** for instance setup.

### Step 2
**Create an S3 Bucket:**
1. Go to the S3 service.
2. Click on **Create bucket**.
3. Provide a unique **Bucket Name** and select the **Region**.
4. Configure additional settings as per requirements and click **Create bucket**.

### Step 3
**Launch EC2 Instance (Linux):**
1. Go to the EC2 service.
2. Click **Launch Instance**.
3. Select an **Amazon Machine Image (AMI)**, such as Amazon Linux 2.
4. Choose an **Instance Type** (e.g., t2.micro).
5. Configure instance settings, key pair, and security groups, then **Launch** the instance.

### Step 4
**Launch EC2 Instance (Windows):**
1. Repeat the EC2 launch steps but select a **Windows Server AMI**.
2. Complete instance configuration and **Launch**.

### Step 5
**Connect to Instances:**
1. **Linux Instance**: Use SSH to connect.
   ```bash
   ssh -i "key_pair.pem" ec2-user@<linux_public_dns>
## Commands
### S3 Bucket Creation
#### 1.AWS CLI Command:
aws s3 mb s3://<your-bucket-name> --region <your-region>
## EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.
## EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

## OUTPUT

### S3 bucket
![s3](https://github.com/user-attachments/assets/a7204359-e6c2-4ef4-a7fd-8b85ab857d97)

### linux instance
![EC2 Instance Connect _ ap-south-1 - Google Chrome 29-08-2024 14_14_25](https://github.com/user-attachments/assets/6b466b45-2c0c-472a-b1ea-e53722e85ea5)

### windows instance
![GOKULwindows - ec2-13-235-94-20 ap-south-1 compute amazonaws com - Remote Desktop Connection 29-08-2024 14_45_25 (1)](https://github.com/user-attachments/assets/77ef84dd-31ce-4d15-950d-86e79db64ce5)



### REG NUMBER:212222230039
### NAME:Gokul R
 
## RESULT
The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.

 

  


