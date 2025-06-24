# Smart Parking Management System (SPMS) 🚗

A cloud-native, microservice-based application designed to solve urban parking challenges using real-time space management, digital payments, and smart tracking.

## 🔍 Overview
Urban environments are overwhelmed by traffic congestion, fuel wastage, and time lost due to inefficient parking systems. SPMS addresses these issues by enabling drivers to easily **search, reserve, and pay** for parking in real time, while allowing parking space owners to manage availability dynamically.

## 🎯 Core Objectives
- Let users find and book available parking spots instantly.
- Allow owners to manage and monitor their parking spaces.
- Track usage by city, zone, and owner.
- Simulate vehicle entries and exits.
- Handle payments and generate receipts.
- Reduce traffic and support smart city goals.

## ⚙️ Architecture

SPMS uses a modular, microservice-based architecture with the following components:

- **🧭 Eureka Service Registry**: For dynamic service registration and discovery.
- **🛠️ Spring Cloud Config Server**: Centralized configuration for all microservices.
- **🌐 Spring Cloud Gateway**: API gateway to route and secure all incoming requests.

### 🧩 Microservices
Each service can be built using Spring Boot / Node.js / Python:
- **Parking Service**: Manage parking spaces, availability, and reservations.
- **Vehicle Service**: Register vehicles and simulate entries/exits.
- **User Service**: Handle user registration, authentication, and history.
- **Payment Service**: Process mock transactions and issue receipts.

## 🧪 Testing

All services are tested using **Postman**, focusing on:
- Functional correctness
- Input validation and error handling
- Service-to-service communication

> 📌 UI is excluded; the focus is solely on backend functionality.

## 🛠️ Tech Stack
- Spring Boot
- Spring Cloud (Eureka, Config, Gateway)
- REST APIs
- Postman (API Testing)

---

> 🚀 SPMS transforms urban parking by enhancing accessibility, reducing congestion, and enabling smart city infrastructure.

[Postman Collection](./postman_collection.json)

✅Eureka Dashboard
![Eureka Dashboard](./docs/screenshots/eureka_dashboard.png)
