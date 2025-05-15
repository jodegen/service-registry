---
# Service Registry (Eureka Server)

This is the central service registry based on Netflix Eureka. It allows all microservices to register themselves and discover other services in a distributed system.

## 🧩 Features

- Spring Cloud Netflix Eureka Server
- Service discovery for all microservices
- Health check & instance management

## 🚀 Technologies

- Java 17
- Spring Boot 3
- Spring Cloud Netflix Eureka

## 🛠️ How to Run

### Docker (Recommended)

```bash
docker build -t service-registry .
docker run -d -p 8761:8761 --name service-registry service-registry
