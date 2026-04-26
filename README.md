
# ☁️ Cloud Computing Internship – Alfido Tech
This repository contains the completed tasks for the **Cloud Computing Internship at Alfido Tech**.
Each task demonstrates hands-on implementation of AWS services including S3, EC2, Lambda, and Docker.

# 📌 Tasks Overview

## 🚀 Task 1: Deploy Static Website on AWS S3

### 🔧 Description

Hosted a static website using AWS S3 with public access enabled.

### ✅ Key Steps

* Created S3 bucket (`aliza-s3-bucket`)
* Enabled static website hosting
* Uploaded HTML file (`index.html`)
* Configured bucket policy for public access
* Accessed website via public URL
---


## 🖥️ Task 2: Deploy Virtual Machine & Web Server

### 🔧 Description

Launched an EC2 instance and hosted a web server using Apache.

### ✅ Key Steps

* Created EC2 instance (`t3.micro`, Ubuntu)
* Configured security group (Ports 22, 80, 443)
* Installed Apache2
* Deployed custom HTML page

### 💻 Commands Used

```bash
sudo apt update -y
sudo apt install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2
sudo systemctl status apache2
```
---


## ⚡ Task 3: Serverless Function using AWS Lambda

### 🔧 Description

Created a serverless function using AWS Lambda and exposed it via API Gateway.

### ✅ Key Steps

* Created Lambda function (`MyFunction`)
* Used Python 3.12 runtime
* Tested using event trigger
* Integrated API Gateway
* Generated public endpoint

### 💻 Sample Output

```json
{
  "message": "Hello from AWS Lambda!",
  "task": "Alfido Tech - Task 3",
  "status": "success",
  "runtime": "Python 3.12"
}
```

---


## 🐳 Task 4: Deploy Docker Container on Cloud VM

### 🔧 Description

Deployed a Docker container running Nginx on an AWS EC2 instance.

### ✅ Key Steps

* Installed Docker on EC2
* Created Dockerfile with Nginx base image
* Built Docker image (`my-nginx-app`)
* Ran container with port mapping
* Accessed application via public IP

### 💻 Docker Commands

```bash
sudo docker build -t my-nginx-app .
sudo docker run -d --name mycontainer -p 80:80 my-nginx-app
sudo docker ps
```

---

# 📸 Deliverables

Each task includes:

* Screenshots of implementation
* Configuration details
* Commands used
* Live deployment links

---

# 🎯 Learning Outcomes

* AWS S3 static hosting
* EC2 instance management
* Web server deployment (Apache)
* Serverless computing (AWS Lambda)
* API Gateway integration
* Docker containerization
* Cloud-based deployment practices

---

# 🏁 Conclusion

This internship provided practical exposure to real-world cloud computing concepts and hands-on experience with AWS services and containerization.

---
