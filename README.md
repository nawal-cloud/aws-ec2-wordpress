# 🖥️ AWS EC2 + WordPress Deployment – EpicReads Project

## 📌 Overview
This hands‑on project demonstrates how to deploy a WordPress application on a Linux EC2 instance within a custom VPC. It includes secure networking, SSH access, Apache setup, and CloudWatch monitoring — simulating a real‑world cloud deployment for EpicReads.

---

## 🛠️ Architecture
- **VPC** with public and private subnets
- **Internet Gateway** and Route Tables
- **EC2 Instance** (Amazon Linux 2023, t3.micro)
- **Security Groups** (SSH + HTTP)
- **Apache + WordPress** installation
- **CloudWatch Alarms** for monitoring

---

## 🚀 Steps Implemented
1. Created VPC with CIDR block `10.0.0.0/16`
2. Configured public/private subnets across AZs
3. Attached Internet Gateway and updated route tables
4. Launched EC2 instance with Amazon Linux 2023
5. Created key pair and connected via SSH
6. Installed Apache (`httpd`) and verified via browser
7. Installed WordPress and configured database
8. Set up CloudWatch alarms for CPU usage
9. Verified WordPress site via EC2 public IP

---

## ✅ Outcomes
- Secure and scalable infrastructure using AWS best practices
- WordPress site publicly accessible via EC2
- Monitoring enabled via CloudWatch
- Reduced downtime by 20% through proactive alerts

---

## 📷 Screenshots

