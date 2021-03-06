+++
title = "Welcome to the MS-SQL Availability Group Workshop"
chapter = false
weight = 1
+++

In this workshop you will learn how to build MS-SQL on EC2 in a well architected fashion.

The workshop is covering the best practices for deploying MS-SQL on EC2 that you can find in [AWS windows user guide](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/aws-sql-clustering.html) and [in AWS whitepaper](https://d1.awsstatic.com/whitepapers/best-practices-for-deploying-microsoft-sql-server-on-aws.pdf)


In this workshop you will deep dive into ways to leverage AWS NVMe drives (locally attached storage) and Amazon EBS Volume striping with Windows Storage Spaces to get more performance & cost effectiveness without compromising on High Availability.

## Main goals

After completing the workshop, you should:

- Be familiar with AWS Directory Service and Amazon FSX for Windows File Server
- Understand how to automate and remotely manage Windows Server
- Be able to build a well-architected self-managed MS-SQL cluster on AWS
- Be able to explore ways to use AWS System Manager to run scripts on servers
- Understand the value of Local NVMe drives and how to use them to get more performance
- Understand the value of striping gp2 and how to automate the process
- Be able to build a full solution for Basic Always On Availability Group with MS-SQL Standard Edition
