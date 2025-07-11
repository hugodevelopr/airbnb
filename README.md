# Airbnb Microservices Architecture (Personal Representation)

Welcome to my personal architectural representation of a platform inspired by [Airbnb](https://www.airbnb.com/). This project was designed to explore **modern microservices architecture**, **domain-driven design**, and **Azure cloud services**, using **C#** as the primary development language.

> ⚠️ **Disclaimer:**  
> This project is **not affiliated**, **endorsed**, or **related to Airbnb, Inc.** in any way.  
> It is a **technical study and personal interpretation** of how such a system could be architected based on publicly known domain concepts.

---

## 🧠 Purpose

This project is part of my portfolio to demonstrate advanced software architecture patterns in a real-world scenario. It aims to:

- Model realistic **bounded contexts** using DDD
- Showcase **event-driven microservices** with asynchronous messaging
- Integrate **Azure-native services** for scalability, reliability, and observability
- Allow for future growth through modular repositories per domain

---

## 📦 Architecture Overview

The system is designed with clear domain boundaries such as:

- `Authentication & Identity`
- `User Profile & Reputation`
- `Listings & Host Management`
- `Reservations & Booking`
- `Payments & Transactions`
- `Messaging & Communication`
- `Reviews & Ratings`
- `Search & Discovery`
- `Analytics & Insights`
- `Support & Help Center`
- `Trust & Safety`
- `Compliance & Data Privacy`
- `Admin & Platform Settings`

Each bounded context will be isolated in its own service/repository to simulate real-world ownership and deployment boundaries.

---

## 📚 Related Repositories

This is the root repository for coordination and documentation. You can find the actual service implementations in the links below:

| Domain Context  | Repository                                                                   | Status        |
|------------------|-----------------------------------------------------------------------------|----------------|
| Web Portal       | [web-portal](https://github.com/hugodevelopr/airbnb-portal)                     | 📝 Planning    |
| API Gateway      | [api-gateway](https://github.com/hugodevelopr/airbnb-gateway)                   | 📝 Planning    |
| Authentication   | [auth-service](https://github.com/hugodevelopr/airbnb-auth-service)             | 📝 Planning    |
| Listings         | [listing-service](https://github.com/hugodevelopr/Airbnb.Services.Listing)       | 🚧 In Progress |
| Booking          | [booking-service](https://github.com/hugodevelopr/airbnb-booking-service)       | 📝 Planning    |
| Payments         | [payment-service](https://github.com/hugodevelopr/airbnb-payment-service)       | 📝 Planning    |
| User             | [user-service](https://github.com/hugodevelopr/airbnb-user-service)             | 📝 Planning    |
| Messaging        | [messaging-service](https://github.com/hugodevelopr/airbnb-messaging-service)   | 📝 Planning    |
| Reviews          | [review-service](https://github.com/hugodevelopr/airbnb-review-service)         | 📝 Planning    |
| Search           | [search-service](https://github.com/hugodevelopr/airbnb-search-service)         | 📝 Planning    |
| Analytics        | [analytics-service](https://github.com/hugodevelopr/airbnb-analytics-service)   | 📝 Planning    |
| Compliance       | [compliance-service](https://github.com/hugodevelopr/airbnb-compliance-service) | 📝 Planning    |
| Support          | [support-service](https://github.com/hugodevelopr/airbnb-support-service)       | 📝 Planning    |
| Trust & Safety   | [trust-service](https://github.com/hugodevelopr/airbnb-trust-service)           | 📝 Planning    |

---

## 🛠️ Tech Stack

- **Language:** C# (.NET 9)
- **Cloud Provider:** Microsoft Azure
- **Architecture:** Microservices, DDD, Event-Driven, Clean Architecture
- **Messaging:** Azure Service Bus
- **Observability:** Azure Monitor, Application Insights
- **CI/CD:** GitHub Actions
- **Infrastructure as Code** Terraform + Bicep

---