### 👋 Hi there, I'm Marcos Vinicius Cardoso

![](https://komarev.com/ghpvc/?username=marcos515&color=fb4362)

**Tech Lead & Software Architect** with 6+ years of experience. I lead a team of 5 developers
modernizing a legacy industrial ERP — written in InterSystems Caché, with 7,500+ classes —
replacing it domain by domain with .NET microservices, GraphQL aggregators and React frontends,
using the Strangler Fig pattern so the business never stops running.

I own the architecture decisions and carry them all the way through: legacy analysis, service mesh
design, messaging contracts, data migration with reconciliation, and Kubernetes deployment.

What makes my range unusual is that I've built complete product chains alone — embedded firmware,
mobile app and cloud backend. That's what lets me make architecture calls without depending on
someone else to explain any layer of the stack. Alongside that, I take on freelance client work
through my own company, delivering entire products end to end by myself.

📄 **Full résumé:** [marcos515.github.io](https://marcos515.github.io/)

---

### 🚀 Featured work

**Legacy ERP modernization** · *Açovisa*
Incremental replacement of an InterSystems Caché ERP by a microservice mesh across 12 business
domains. Each module owns its API (.NET 10 + EF Core + PostgreSQL, schema per service), a GraphQL
aggregator that composes reads and delegates writes, and a React frontend. Transactional outbox on
RabbitMQ with DLX/DLQ and `messageId` deduplication; anticorruption layer over the read-only legacy.

**Smart pool lighting** · *freelance client project* · Flutter · ESP32 · AWS IoT
RGB lamp control system shipped on Android. A single Flutter app discovers the lamp over Bluetooth,
provisions its network credentials and moves control to the cloud — switching between local BLE and
remote MQTT without losing scenes, schedules or devices. I built the whole chain: firmware,
communication protocol, mobile app and serverless backend.

**Forensic services marketplace** · *freelance client project* · React · AWS
SaaS platform connecting law firms and companies to forensic experts and investigators. Delivered
end to end and solo: business and contract modeling, serverless AWS architecture, React frontend and
infrastructure as code — with managed auth, queue-based processing, reputation ranking and payments.

**Predictive maintenance for industrial assets** · *Açovisa* · ESP32 · AWS IoT · Grafana
Vibration sensors built from the firmware up: ESP32 with accelerometer, BLE read protocol and a
Flutter app for field collection, evolved into a platform with AWS IoT ingestion, Grafana dashboards
and AI-based anomaly detection — anticipating asset failure instead of reacting to breakdowns.

**Applied AI** · *Açovisa*
Multi-tenant agent runtime, RAG pipeline with embeddings, MCP servers exposing ERPs as tools for
language models, and industrial video analytics with VLLMs.

---

### 🛠️ Stack

**Architecture** — Microservices · Event-driven architecture · Strangler Fig · Anticorruption layer ·
Transactional outbox · Idempotency and deduplication · Legacy system migration

**Languages** — C# · Python · TypeScript · JavaScript · Java · Dart · C/C++ · SQL

**Backend** — .NET / ASP.NET Core · Entity Framework Core · FastAPI · Flask · Spring Boot · Node.js ·
REST · GraphQL

**Frontend & Mobile** — React · Next.js · Vite · Flutter · Riverpod · React Native · Expo

**Data** — PostgreSQL · SQL Server · MongoDB · DynamoDB · Redis · InterSystems Caché

**Messaging** — RabbitMQ · Kafka · MQTT · Bluetooth Low Energy

**Cloud & DevOps** — Azure (AKS, ACR, Blob) · AWS (Lambda, IoT Core, API Gateway, DynamoDB, Cognito,
SQS, SES, CDK) · Docker · Kubernetes · Azure DevOps · CI/CD · Grafana · Linux

**Embedded & IoT** — ESP32 · ARM Cortex-M · LoRa · RTOS · Modbus · CAN Bus

**AI** — LLMs and VLLMs · RAG · Embeddings · Model Context Protocol · Computer vision · Anomaly detection

**Security** — SSO with httpOnly cookies · JWT · OAuth · LDAP · Permission-based authorization ·
Secret management

---

### 🏆 Achievements

- 🥈 **2nd place** — Microsoft AI Challenge with SENAI, Veterans category (7,000+ participants across ~1,400 teams)
- 🥈 **2nd place** — BRICS FutureSkills Challenge, IoT
- 🥈 **2nd place** — AWS JAM 2022
- 🏅 **4th place** — 8th WorldSkills Russia National Competition, IoT

---

### 📚 Education

**B.Sc. in Computer Science** · UNIP · 2019–2023
**Technical Degree in Information Technology** · SENAI São Paulo · 2020–2022

---

### 🌐 Find me around the web

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos515)
[![Website](https://img.shields.io/badge/-marcos515.github.io-1f3a5f?style=flat-square&logo=githubpages&logoColor=white)](https://marcos515.github.io/)

Feel free to reach out — always open to conversations about technical leadership, architecture and
legacy modernization.
