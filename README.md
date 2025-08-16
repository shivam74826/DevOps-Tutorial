# DevOps-Tutorial
AWS Solution Architect -Full Tutorial Roadmap.

📍 Chapter: 1 Foundations
* What is cloud Computing(Ias, Pass, Saas)
* AWS Global infrastruture --> Regions, AZs, edge locations.
* Shared responsibility model(AWS vs. Customer responsibilities)
* AWS Free tier & pricing model.

📍 Chapter 2: Core Compute
* EC2 (Elastic compute cloud)
   > Lunch type, AMIs, EBS Volumes, Security Groups
   >  Auto Scalling Group(ASG)& Elastic Load Balancer(ALB/NLB).
* Elastic Bean Stack - Managed Deployments
* Lambda - Serverless compute.

📍 Chapter 3: Storage
* S3 Simple storage service.
   > Buckets, objects, storage classes, versioning, Life cycle policies.
   > Static website hosting, Pre-singed urls.
* Elastic Block store vs. EFS (Elastic File System)
* Glacier for archival.

📍 Chapter 4: Databases
* RDS (Relational Database Service) - Multi-AZ, Read Replicas, Backup.
* Aurora - High-performance RDS engine.
* DynomoDB - NoSQL, Global Tables, DAX.
* Elasti Cache - Redis/Memcached.

📍 Chapter 5: Networking
* VPC (Virtual Private Cloud)
   > Subnet (Public, Private), Route Tables, IGW, Nat Gateway.
   > Security Groups VS. NACLs.

* VPC Peering, Transit Gateway.
* Route 53 - DNS & Routing Policies (Simple, Weighted, Latency, Failover, geolocation. etc.)
* Cloud Front (CDN)

📍 Chapter 6: IAM & Security
* IAM Users, Groups, Roles, Policies
* MFA, Least Privilege Principle
* KMS (Key Management Service)
* Secret Manager / Parameter Store
* Organizations & SCPs ( Service Control Polices )

📍 Chapter 7: Monitoring & Managment
* CloudWatch - Metrix, logs, alarms, dashboards.
* CloudTrail - auditing & API logs.
* Trusted Advisor - best practice checks.
* Config - compliance monitoring.

📍 Chapter 8: High Availability & Scaling
* Multi-AZ & Multi-Region design patterns.
* Elastic Load Balancing + Auto Scalling
* RTO/RPO concepts (Disaster Recovery strategies: Backup/Restore, Pilot Light, Warm)
* Standby, Multi-site Active-Active.

📍 Chapter 9: Cost Optimization
*  EC2 pricing models -> on demand, Reserved, spot, Saving Plans
*  Right-Sizing workloads
*  S3 lifecycle & Glacier for cost saving
*  AWS Pricing Calculator

📍 Chapter 10: Architecture Patterns
* 3-Tier Web Application on AWS
* Serverless Application (API Gateway + Lambda + DynamoDB + S3)
* Highly Available Wordpress on AWS
* Hybrid Cloud Setup(VPN, Direct Connect)

📍 Chapter 11: Exam Preparation ( if Targeting SAA-C03)
* Practice Questions on Well-Architected Framework (5 pillars)
   > Operational Excellence
   > Security
   > Reliability
   > Performance Efficiencny
   > Cost Optimization

