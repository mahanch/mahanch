# 👋 Hi, I'm “mahan”

Backend engineer focused on .NET Core, designing domain-centric, scalable, and clean systems. My core expertise includes Domain-Driven Design (DDD), CQRS, Clean Architecture, Microservices, and Onion Architecture. I use HangFire for background processing and complement my .NET work with Flutter (for cross‑platform UI) and Python (for computer vision and face analytics).

---

## 🎯 Engineering Philosophy
- Domain-Driven Design (DDD): Domain-first, ubiquitous language, Bounded Contexts, and strong business invariants.
- CQRS & Event-Driven: Separate read/write models, leverage messaging for scalability and decoupling.
- Clean & Onion Architectures: Clear boundaries, framework independence, and high testability.
- Microservices: Autonomous services with well-defined boundaries, independent deployment, and resilient communication.
- Background Processing: Reliable job scheduling, retries, and monitoring with HangFire.
- Observability: Structured logging, tracing, and actionable metrics for production reliability.
- Quality: Unit/integration tests, CI/CD, code reviews, and consistent coding standards.

---

## 🛠️ Skills & Tools
- .NET 6/7/8, ASP.NET Core, EF Core, LINQ
- Architectures: DDD, CQRS, Clean Architecture, Microservices, Onion Architecture
- Libraries/Patterns: MediatR, AutoMapper, FluentValidation
- Auth/Security: JWT, ASP.NET Identity
- Messaging & Cache: RabbitMQ/Kafka, Redis
- Service Communication: REST, gRPC
- Databases: SQL Server, PostgreSQL
- DevOps: Docker, Kubernetes (K8s), GitHub Actions
- Background jobs: HangFire, Quartz.NET
- Testing: xUnit and Integration testing
- Frontend/Mobile: Flutter (Dart)
- Data/ML: Python (Face Detection/Embedding)

---


## 🔗 .NET + Flutter + Python Synergy
- .NET Core as the backbone: secure, scalable, and testable backend services.
- Flutter for fast cross‑platform UI: smooth user experiences, integrated with robust APIs.
- Python for AI/CV: model‑driven services communicating with .NET via REST/gRPC for face detection/embedding.

---

## 🧩 Suggested Project Layout
```text
src/
  ├─ Presentation (API, gRPC, UI)
  ├─ Application (Use Cases, DTOs, Mediators)
  ├─ Domain (Entities, Value Objects, Aggregates, Domain Events, Repository Interfaces)
  ├─ Infrastructure (EF Core, Messaging, Caching, External Integrations)
  └─ BackgroundJobs (HangFire Jobs, Schedulers)
tests/
  ├─ UnitTests
  └─ IntegrationTests
```
- Bounded Contexts as separate packages/services for microservice boundaries.
- Each service with independent deployment config and dedicated CI/CD pipeline.

---

## 📈 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mahanch&show_icons=true&theme=transparent)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mahanch&layout=compact&theme=transparent)

---

## 🤝 Collaboration & Contact
- Interested in domain‑centric architectures, scalable services, and .NET + Flutter + Python integrations? Let’s collaborate.
- Contact: please open an [Issue](https://github.com/mahanch/mahanch/issues) or message via GitHub.  
  (Add your email/social links here if you prefer.)

---

## 🧭 Short Roadmap
- Strengthen observability (tracing/logging) across services
- Improve integration, contract, and end‑to‑end testing
- Document Bounded Contexts and inter‑service communication patterns
- Upgrade .NET versions and performance tuning

---

> Note: To display this README on your profile, create the special repository `mahanch/mahanch` and add this file as `README.md`. If you want more customization or sections (e.g., achievements, certifications, tech blog links), tell me and I’ll tailor it.
