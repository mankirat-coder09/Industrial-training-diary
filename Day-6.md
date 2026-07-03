# ☁️ Day 6 – AWS and Docker Intro & Project

> **Training Diary – Day 6**

## 🎯 Objective

The objective of today's session was to understand the basics of cloud computing using AWS and containerization using Docker. The session also included a practical project to understand how applications are deployed in real-world environments using containers.

---

# 📚 Topics Covered

## ☁️ AWS (Amazon Web Services) – Introduction

- Introduction to Cloud Computing
- What is AWS?
- Benefits of Cloud Computing
- AWS Global Infrastructure
- Common AWS Services Overview:
  - EC2 (Virtual Servers)
  - S3 (Storage Service)
  - IAM (Identity and Access Management)
- Basics of deploying applications on cloud
- Introduction to scalable architecture

---

## 🐳 Docker – Introduction

- What is Docker?
- Containers vs Virtual Machines
- Docker Architecture
- Docker Images and Containers
- Dockerfile basics
- Docker commands:
  - `docker build`
  - `docker run`
  - `docker ps`
  - `docker stop`
- Benefits of containerization
- Use of Docker in modern AI/DevOps workflows

---

# 💻 Hands-on Project

## 🚀 Containerized AI/Flask Application using Docker

### Project Description

Developed and containerized a simple **Flask-based AI application** using Docker. The project demonstrates how applications can be packaged with all dependencies and run consistently across different environments.

### 🛠️ Technologies Used

- Python
- Flask
- Docker
- Dockerfile
- Ubuntu-based container

---

### 📦 Project Workflow

1. Created a Flask application
2. Defined project dependencies in `requirements.txt`
3. Created a `Dockerfile`
4. Built Docker image
5. Ran application inside a Docker container

---

### 🐳 Dockerfile Example

```dockerfile
FROM python:3.10

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
```

---

### ✨ Features

- Containerized application
- Portable and environment-independent setup
- Easy deployment using Docker
- Consistent runtime across systems

---

### 📚 Skills Learned

- Basics of AWS cloud computing
- Understanding of virtualization vs containers
- Docker image creation
- Running applications inside containers
- Real-world deployment workflow

---

# 📖 Learning Outcome

By the end of today's session, I was able to:

- Understand cloud computing fundamentals and AWS basics.
- Learn core AWS services like EC2, S3, and IAM.
- Understand Docker and containerization concepts.
- Build and run a containerized Flask application.
- Learn how Docker simplifies deployment across environments.

---

# 💡 Key Takeaways

- Cloud computing enables scalable and flexible infrastructure.
- AWS is one of the most widely used cloud platforms.
- Docker ensures applications run consistently anywhere.
- Containers are lightweight alternatives to virtual machines.
- Modern AI and software systems rely heavily on cloud + containerization.

---

# 🚀 Summary

Day 6 introduced **Cloud Computing (AWS)** and **Containerization (Docker)** along with a practical hands-on project. The session helped in understanding how modern applications are deployed and managed efficiently using cloud infrastructure and containers.

---

## 🛠️ Technologies Used Today

- AWS (EC2, S3, IAM basics)
- Docker
- Python
- Flask
- Dockerfile
- Linux environment

---

## 📅 Training Details

| Training Program | 1-Month AI Training |
|------------------|---------------------|
| Day | 06 |
| Topic | AWS and Docker Intro & Project |
| Practical Work | Dockerized Flask Application |

---

⭐ **Day 6 Complete**
