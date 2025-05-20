# AWS-OpenVPN

<h2>Description</h2>
This project focused on the secure deployment of an OpenVPN server within the AWS cloud environment, utilizing an Amazon EC2 instance hosted in a segmented Virtual Private Cloud (VPC). The architecture included public and private subnets, custom security groups, and a Linux-based EC2 instance configured with OpenVPN to enable secure, encrypted remote access. Identity and Access Management (IAM) policies were applied following the principle of least privilege, with role-based access control to support operational and administrative functions. Redundancy and availability were achieved through scheduled backups using AWS Backup and encrypted AMI snapshots stored in Amazon S3. Monitoring and alerting were implemented with Amazon CloudWatch and SNS to detect and respond to anomalous traffic patterns. Security posture was further enhanced through the use of Amazon Inspector and adherence to the AWS Well-Architected Framework. Additional considerations included automation with AWS Lambda, MFA enforcement, and the development of a comprehensive incident response plan aligned with NIST 800-61r3.
<br />

<h2>Main Services Used</h2>
- <b>Amazon EC2</b>
<br />
- <b>Amazon S3</b>
<br />
- <b>AWS Backup</b>
<br />
- <b>AWS Identity and Access Management</b>
<br />
- <b>Amazon CloudWatch</b>
<br />
- <b>Amazon Inspector</b>

<h2>Report and Screenshot PDFs</h2>

