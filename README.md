# 📡 Cloud-Based Microservices for a Nationwide Radio

## 🚀 Project Overview
This project consists of **cloud-native microservices** designed to support a **nationwide radio station**, enabling it to reach remote areas with minimal infrastructure costs. Originally planned for AWS, the architecture was adapted to **cost-efficient open-source solutions** due to financial restrictions. The system leverages **Spring Boot, Apache Kafka, API Gateway, Zipkin, Circuit Breaker, and Jenkins** to ensure scalability, resilience, and observability.

## 🏗️ Architecture
### **Main Components**:
- **API Gateway**: Manages and secures API requests, directing traffic to the appropriate microservices.
- **Spring Boot Microservices**: Modular services handling different functionalities (e.g., user management, streaming, advertisement delivery).
- **Apache Kafka**: Enables asynchronous communication and event-driven architecture.
- **Zipkin**: Provides distributed tracing to monitor request flows across services.
- **Circuit Breaker (Resilience4j)**: Prevents cascading failures by handling unstable network connections.
- **Jenkins (CI/CD)**: Automates testing and deployment for seamless updates.
- **Database (MySQL/PostgreSQL)**: Stores user data, logs, and streaming metadata.

## 🎯 Features
✅ **Cloud-native microservices** for high availability and scalability.  
✅ **Event-driven architecture** using Apache Kafka for real-time processing.  
✅ **API Gateway integration** for efficient request routing and security.  
✅ **Observability tools** like Zipkin to monitor and troubleshoot requests.  
✅ **Resilient infrastructure** using Circuit Breaker to ensure uptime in unstable environments.  
✅ **Automated CI/CD pipelines** with Jenkins for smooth deployments.  

## 🏗️ Deployment
### **Prerequisites**:
- Docker & Docker Compose
- Java 19
- Jenkins (for CI/CD pipeline)
- MySQL/PostgreSQL
- Apache Kafka

### **Setup**:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nationwide-radio.git
   cd nationwide-radio
   ```
2. Start services with Docker Compose:
   ```bash
   docker-compose up -d
   ```
3. Access the services:
   - API Gateway: `http://localhost:8080`
   - Zipkin UI: `http://localhost:9411`
   - Kafka UI (if configured): `http://localhost:9000`

## 📌 Usage
- API endpoints are available via **API Gateway**.
- Services communicate asynchronously via **Apache Kafka**.
- Observability can be checked using **Zipkin traces**.
- Logs and monitoring are accessible via the configured observability stack.

## 📄 Documentation
Refer to the [Wiki](https://github.com/yourusername/nationwide-radio/wiki) for detailed API documentation and architecture diagrams.

## 🤝 Contributing
Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## 🏆 Acknowledgments
This project is part of my **AWS Cloud & DevOps journey** and showcases my expertise in **cloud computing, microservices, and CI/CD automation**.

