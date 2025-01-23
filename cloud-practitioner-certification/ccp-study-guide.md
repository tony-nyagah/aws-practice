# AWS Cloud Practitioner Exam Study Guide

## 1. Exam Structure
- Duration: 90 minutes
- Questions: 65 (50 scored, 15 unscored)
- Passing score: 700/1000 (approximately 70%)
- Format: Multiple choice and multiple response
- Note: No penalty for wrong answers

## 2. Core Concepts (24% of exam)

### Cloud Computing Basics
#### 6 Advantages of Cloud:
1. Trade fixed expense for variable expense
2. Benefit from massive economies of scale
3. Stop guessing capacity
4. Increase speed and agility
5. Stop spending money running/maintaining data centers
6. Go global in minutes

### Shared Responsibility Model
- AWS Responsibilities (Security OF the Cloud):
  - Physical security
  - Infrastructure
  - Network security
- Customer Responsibilities (Security IN the Cloud):
  - Data encryption
  - Network traffic
  - Operating systems
  - Applications

## 3. Security and Compliance (30% of exam)

### Key Security Services
#### IAM (Identity and Access Management)
- Users, Groups, Roles, Policies
- Root user should never be used for daily tasks
- MFA for additional security

#### Other Security Services
- AWS WAF (Web Application Firewall)
- Shield (DDoS protection)
- CloudWatch (Monitoring)
- CloudTrail (API Logging)

## 4. Core Services (34% of exam)

### Compute
#### EC2 (Virtual Servers)
- Different instance types (t2.micro, etc.)
- Pay as you go
- Pricing models:
  - On-demand
  - Reserved
  - Spot

#### Lambda (Serverless)
- Pay per execution
- No server management

### Storage
#### S3 (Simple Storage Service)
- Object storage
- Storage classes:
  - Standard
  - Infrequent Access (IA)
  - Glacier
- Durability: 99.999999999%

### Database
- RDS (Relational Database Service)
- DynamoDB (NoSQL)

### Networking
- VPC (Virtual Private Cloud)
- Route 53 (DNS service)

## 5. Billing and Pricing (12% of exam)

### Pricing Models
- Pay-as-you-go
- Save when you reserve
- Pay less by using more
- Free tier available

### Support Plans
- Basic (Free)
- Developer ($29/month)
- Business ($100/month)
- Enterprise ($$$$)

## Exam Success Tips
1. When in doubt, choose the most cost-effective or secure option
2. AWS always promotes high availability and fault tolerance
3. Cost optimization questions usually point to Reserved Instances or Savings Plans
4. Security questions often relate to the Shared Responsibility Model
5. Look for keywords like "most cost-effective," "highly available," or "secure"

## Sample Practice Question
Q: A company wants to store data that is infrequently accessed but needs to be immediately available when needed. Which S3 storage class should they use?
A: S3 Standard-IA (Infrequent Access)