# AWS-Project-2
Publishing Amazon SNS Messages Privately

🏥 Secure Patient Report Delivery using AWS SNS

📌 Industry
Healthcare

📌 Problem Statement
Hospitals need a secure way to send patient records online and ensure they are delivered privately to the intended party. The challenge is to build a platform where patients can access their reports via mobile devices and receive push notifications, while maintaining strict privacy and security standards.

📌 Project Overview

This project demonstrates how to securely publish patient reports using Amazon SNS within a private VPC hosted on AWS EC2. By leveraging AWS services, the solution ensures:
Secure storage and transmission of patient records
Private message publishing through Amazon SNS
Improved delivery and receipt of reports with push notifications
Patients can access their reports via mobile applications, ensuring convenience without compromising privacy.

🚀 Highlights

AWS CloudFormation – Automated creation of a secure VPC.
Amazon SNS Integration – Connecting the VPC with SNS for private message publishing.
Private Report Delivery – Reports hosted on EC2 and published securely via SNS.

🛠️ Tech Stack

AWS CloudFormation – Infrastructure as Code (IaC)
Amazon VPC – Secure networking environment
Amazon EC2 – Hosting patient report services
Amazon SNS – Private message publishing and push notifications

🔒 Security Considerations

End-to-end encryption for patient records
Private VPC setup to restrict unauthorized access
IAM roles and policies for secure access management
HTTPS communication for secure data transfer

📱 Features

Patients receive push notifications when reports are available
Reports accessible via mobile devices securely
Private publishing ensures only intended recipients receive the data

⚙️ How to Run

Deploy the VPC using CloudFormation templates.
Launch EC2 instance within the VPC.
Configure SNS topic and subscriptions for private publishing.
Upload patient reports to EC2 and publish notifications via SNS.
Access reports securely via mobile app with push notifications.

📈 Future Enhancements

Integration with AWS Lambda for serverless automation
Multi-factor authentication for patient access
Audit logging for compliance with healthcare regulations (HIPAA, GDPR)

📌 Impact

This project demonstrates how cloud-native architecture can transform healthcare operations by combining security, scalability, and patient convenience. It showcases best practices in AWS infrastructure design and highlights the importance of privacy-first solutions in sensitive industries.
