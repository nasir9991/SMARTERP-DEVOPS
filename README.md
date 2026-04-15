# SmartERP DevOps 🚀

## 📌 Description
SmartERP is an enterprise-level web application designed to manage business operations efficiently. This project focuses on implementing DevOps practices to automate deployment, improve scalability, and ensure reliable infrastructure.

## 🛠 Tech Stack
- AWS (EC2, S3, IAM)
- Docker
- Kubernetes
- Jenkins CI/CD
- Linux (Ubuntu)
- Bash Scripting

## 🚀 Features
- Automated CI/CD pipeline using Jenkins
- Containerized applications using Docker
- Scalable deployment using Kubernetes
- Infrastructure management on AWS
- Secure access using IAM roles and policies

## ⚙️ DevOps Workflow
1. Code pushed to GitHub
2. Jenkins pipeline triggered
3. Docker image built
4. Deployment to Kubernetes cluster
5. Monitoring and logging enabled

## 🔧 Setup Instructions
```bash
# Clone repo
git clone <your-repo-link>

# Build Docker image
docker build -t smarterp .

# Run container
docker run -p 5000:5000 smarterp
