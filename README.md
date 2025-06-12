# CLOUD-SPACE-STORAGE

**COMPANY**: CODETECH IT SOLUTIONS

**NAME**: PAVATHAARINI A

**INTERN ID** : CT04DG907

**DOMAIN** :Cloud Computing

**DURATION**: 4 WEEKS

**MENTOR**:Neela Santhosh Kumar




Amazon S3 (Simple Storage Service) is a highly scalable, durable, and secure object storage service offered by Amazon Web Services (AWS). It's designed to store and retrieve any amount of data from anywhere on the web.
Core Concepts:
Buckets: The fundamental containers for storing data in S3. Think of them as top-level folders. Each bucket name must be globally unique across all AWS accounts. You specify an AWS Region for your bucket, which impacts latency and compliance.

Objects: The actual data stored in S3. An object consists of the data itself (e.g., a file, image, video) and its associated metadata (e.g., content type, creation date). Each object has a unique key within its bucket.

Creating an S3 Bucket:
Log in to the AWS Management Console: Access your AWS account.
Navigate to the S3 Service: Find S3 in the list of services or search for it.
Click "Create bucket": This initiates the bucket creation wizard.
Enter a unique bucket name: Choose a globally unique name following AWS naming conventions.
Select an AWS Region: Choose a region geographically close to your users for optimal performance and to meet data residency requirements.
Configure additional settings (optional but recommended):
Object Ownership: It's best practice to set this to "Bucket owner preferred" to ensure the bucket owner always has full control over objects uploaded to the bucket.
Block Public Access: By default, S3 buckets are private. It's highly recommended to keep "Block all public access" enabled unless your use case explicitly requires public access (e.g., static website hosting), and even then, apply the principle of least privilege.

Bucket Versioning: Enable this to keep multiple versions of an object in the same bucket. This provides a safety net against accidental deletions or overwrites, allowing you to restore previous states.

Default Encryption: Enable server-side encryption (SSE-S3, SSE-KMS, or SSE-C) to automatically encrypt all new objects uploaded to the bucket. This is crucial for data security at rest.
Tags: Apply tags for cost allocation, organization, and access control.
Review and Create: Verify your settings and click "Create bucket."
Configuring S3 Storage (Best Practices):
Access Control:
Least Privilege: Grant only the necessary permissions to users and applications using AWS Identity and Access Management (IAM) policies and S3 bucket policies. Avoid overly permissive ACLs.
Block Public Access: As mentioned, keep public access blocked unless absolutely essential.
MFA Delete: Enable Multi-Factor Authentication (MFA) Delete for critical buckets to require an MFA token for permanent object deletions or versioning state changes.
Data Protection:
Encryption: Always encrypt data at rest (default bucket encryption) and in transit (using HTTPS/SSL/TLS).
Versioning: Enable versioning to protect against accidental data loss.
Lifecycle Management: Implement lifecycle rules to automatically transition objects to cheaper storage classes (e.g., S3 Standard-IA, S3 Glacier) or expire them after a certain period, optimizing costs.
Replication: For disaster recovery and compliance, configure S3 Replication to replicate data to different AWS accounts or regions.
Monitoring and Logging:
Server Access Logging: Enable server access logging to record detailed requests to your S3 buckets. This is vital for security audits, troubleshooting, and compliance.
CloudWatch: Monitor S3 metrics (e.g., storage usage, number of requests, errors) using AWS CloudWatch and set up alerts for unusual activity.
CloudTrail: Use AWS CloudTrail to log API calls and related events made to S3, providing an audit trail of actions taken.
Storage Classes: Choose the appropriate S3 storage class based on your access patterns and cost requirements (e.g., S3 Standard for frequently accessed data, S3 Intelligent-Tiering for unknown access patterns, S3 Glacier for archiving).

**OUTPUT**

![Image](https://github.com/user-attachments/assets/79cc2339-e117-4f15-b578-e21fbcb50de3)
![Image](https://github.com/user-attachments/assets/1459ae19-a1a0-4e74-a5ff-0b22eb69d12c)
![Image](https://github.com/user-attachments/assets/6836c71f-7720-4c39-9f9f-0c97d96def69)
![Image](https://github.com/user-attachments/assets/d3bd027c-96a9-493a-bf19-4b4b3aa204a8)
![Image](https://github.com/user-attachments/assets/3a2e0484-961d-4314-a126-066513c33b2f)
![Image](https://github.com/user-attachments/assets/ae2e1328-4337-42b6-afd3-1c80385df855)
![Image](https://github.com/user-attachments/assets/93b060da-cfba-43fc-9e46-fac93b87f307)
![Image](https://github.com/user-attachments/assets/bf9ef0b4-e2e6-4786-83db-4ccfb84164b2)
![Image](https://github.com/user-attachments/assets/0de13179-fa52-4ec9-92ac-09d6e3e7a9b4)
