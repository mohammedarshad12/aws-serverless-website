# AWS Serverless Web Application 

This project showcases a **fully serverless web application** built on **Amazon Web Services (AWS)** using **API Gateway**, **AWS Lambda (Python 3.8)**, and **Amazon DynamoDB** — with a clean and responsive **HTML/CSS frontend**.

## 🚀 Project Overview

This application demonstrates how a simple form-based web app can be completely serverless, scalable, and cost-efficient using AWS managed services.

### 🧱 Architecture Summary

| Layer | Description |
|-------|--------------|
| **Frontend** | HTML/CSS-based form hosted on Amazon S3 for user interaction |
| **API Layer** | Amazon API Gateway exposes RESTful endpoints for form submission |
| **Server Layer** | AWS Lambda (Python 3.8) processes user data, validates inputs, and interacts with DynamoDB |
| **Backend** | Amazon DynamoDB securely stores form submissions |
| **Security** | AWS IAM roles manage least-privilege access between all services |

---

## 🏗️ Architecture Diagram
Frontend (HTML/CSS)
│
▼
Amazon API Gateway (REST API)
│
▼
AWS Lambda (Python 3.8)
│
▼
Amazon DynamoDB (Data Storage)
