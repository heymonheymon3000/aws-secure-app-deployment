# Secure App Deployment

## 🌟 Overview
**Scenario**</br>
SecureCart is a fast-growing e-commerce platform that initially launched with a focus on speed rather than security. As a result, its infrastructure left key resources - EC2, S3, and RDS, exposed directly to the public internet. With over 10,000 customers, SecureCart now faces significant risks including unauthorized access, data breaches, and compliance issues. A secure cloud redesign is urgently needed.

**Your Role**
In this project, you’ll act as a cloud security-focused Solutions Architect. Your mission is to take a vulnerable cloud environment and transform it into a secure, production-ready architecture using AWS-native tools and best practices.

We’ll begin by deploying the **insecure baseline**, exposing common mistakes. Then, you’ll rebuild the entire setup step by step, following security-first design principles aligned with the **AWS Well-Architected Framework**.

## 🛠️ Services used
* **Amazon VPC**: Isolate application layers and control traffic using private/public subnets
* **Amazon EC2**: Host the application backend, migrated to private subnets
* **Amazon RDS**: Secure relational database with encryption and private access
* **Amazon S3**: Object storage configured with private access only
* **AWS CloudFront**: Secure content delivery with HTTPS enforcement
* **AWS IAM**: Role-based access control with least-privilege enforcement
* **Application Load Balancer (ALB)**: Public endpoint forwarding to private app
* **AWS WAF**: Adds basic protection against common Layer 7 threats

## ☁️ AWS Architecture

## &rarr; Final Result

<!-- ![alt text](design/igw.png) -->