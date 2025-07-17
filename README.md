# 🏥 Patient Management System - Microservices Architecture (Java + Spring Boot + AWS)

This is a production-ready **Patient Management System** built with **Java Spring Boot**, following a modern **Microservices architecture**. It includes complete end-to-end features such as patient management, authentication, billing, analytics, and cloud infrastructure deployment using **AWS CloudFormation**, **Docker**, **gRPC**, **Kafka**, and more.

---

## 🚀 Features

- ✅ **Patient Service**: Create, update, delete, and retrieve patient records.
- 🔐 **Auth Service**: Secure login using JWT and Spring Security.
- 💰 **Billing Service**: Handles billing logic, communicates via gRPC.
- 📊 **Analytics Service**: Consumes patient events via Kafka and processes them.
- 📦 **API Gateway**: Routes requests and handles authentication centrally.
- 📡 **Inter-service Communication**:
  - gRPC for synchronous requests.
  - Apache Kafka for asynchronous events.
- 🐳 **Dockerized Microservices**: Each service is containerized for scalable deployment.
- ☁️ **AWS Infrastructure**:
  - Deployed with **CloudFormation**
  - Uses **ECS**, **VPC**, **RDS**, **MSK (Kafka)**, **API Gateway**
- 🧪 **Integration & Unit Testing**: Secure and tested endpoints across services.

---

## 🛠️ Tech Stack

- **Languages**: Java 17
- **Frameworks**: Spring Boot, Spring Security
- **Communication**: gRPC, Kafka
- **Authentication**: JWT
- **Database**: PostgreSQL (via RDS)
- **Infrastructure**: AWS CloudFormation, ECS, MSK, VPC
- **Containerization**: Docker
- **Dev Tools**: LocalStack, Postman, AWS CLI

---

## 🧱 Microservice Architecture

![image alt](https://github.com/patelaviral/Patient_Management_System/blob/3ace8de086cbce83d117b837dc3139f3ae00d5c7/Architecture_of_PMS.png)
