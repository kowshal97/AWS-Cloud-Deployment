# ☁️ AWS Final Test Project – Cloud Deployment  

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)  
![Cloud](https://img.shields.io/badge/Cloud-AWS-orange)  
![Architecture](https://img.shields.io/badge/Design-3Tier-blue)  
![Database](https://img.shields.io/badge/Database-PostgreSQL-lightblue)  
![Scaling](https://img.shields.io/badge/AutoScaling-Enabled-success)  

---

## 📌 Overview  
This project is part of my **Final Test submission** for the Cloud Computing.  
It demonstrates how to design and deploy a **secure, highly available 3-tier architecture** on AWS with auto scaling and database recovery.  

---

## 🚀 Deliverables  
- 🌐 **Custom VPC** with public and private subnets across multiple AZs  
- 💻 **EC2 Instances** running Apache/PHP  
- ⚖️ **Application Load Balancer (ALB)** for distributing traffic  
- 📈 **Auto Scaling Group (ASG)** (min: 2, max: 5) with CPU scaling  
- 🗄️ **Aurora PostgreSQL Database** in private subnet  
- 📦 **Backups & Point-in-Time Recovery (PITR)** enabled  
- 🔐 **IAM Roles & Security Groups** following least privilege  

---

## 🛠️ Architecture  
The deployment followed a **3-tier model**:  

1. 🏗️ **Networking Layer** → VPC, Subnets, Route Tables, Internet Gateway, NAT  
2. ⚙️ **Application Layer** → EC2 with Apache/PHP, custom AMI for scaling  
3. 💾 **Database Layer** → Aurora PostgreSQL cluster, PITR enabled  

---

## 📂 Repository Contents  
📄 **Final_test.docx / PDF** → Detailed report with steps, screenshots, and results  
📝 **README.md** → Project documentation (this file)  

---

## 🧰 Technologies Used  
- ☁️ AWS: VPC, EC2, ALB, RDS Aurora, Auto Scaling, CloudWatch  
- 🗄️ PostgreSQL  
- 🐧 Linux (Amazon Linux 2), Apache, PHP  

---

## 📸 Screenshots  
(Add your architecture diagram + AWS console screenshots + scaling proof here)  

---

## 🎯 Key Learnings  
- ✅ Designed a **secure, multi-AZ AWS architecture**  
- ✅ Configured **load balancing + auto scaling** for high availability  
- ✅ Implemented **RDS Aurora backups + PITR**  
- ✅ Gained strong **hands-on cloud deployment skills**  

---

## 👤 Author  
**Kowshal Sugunarajah**  
🎓 Postgraduate Student – Cloud Computing @ Durham College  
💼 Ex-QA at Amazon | ☁️ Cloud Enthusiast | 🗄️ Database & Automation Tester  
