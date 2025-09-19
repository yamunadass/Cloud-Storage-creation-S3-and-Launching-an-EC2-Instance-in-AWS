## Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS

```
Name         : YAMUNA M
Register No. : 212223230248
```
 ## Aim:
 
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 

## Procedure:

a)	Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console

  Go to https://console.aws.amazon.com/s3.
  
Step 2: Open the S3 Service

  In the console, type S3 in the search bar and select S3 to open the service dashboard.
  
Step 3: Create Bucket

  Click the Create bucket button.
Step 4: Configure Bucket Settings

•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership

Choose between:

	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.

Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).

Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.

Step 10: Create the Bucket
Click Create bucket at the bottom of the page.

b)	i. Steps to launch an EC2 Instance

1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance

•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


## Snap Shots:
 

Snap Shot 1: 

<img width="1004" height="539" alt="image" src="https://github.com/user-attachments/assets/7bcbc34a-925f-45be-b177-e82e38f39bbc" />

Simple Storage Service (S3)
 

Snap Shot 2: 

<img width="981" height="583" alt="image" src="https://github.com/user-attachments/assets/3f6f7b88-7425-4179-a1e3-bc1a85fb1372" />

EC2 (Elastic Compute Cloud) – Instance

## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
