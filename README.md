# ShopAI : Cloud-Native-AI-Powered-Commerce-Platform

Tech stack Include : Angular,ASP.NET Core / C# , Microservices, EF Core + PostgreSQL / SQL Server, RabbitMQ + MassTransit, Redis , Docker + .Net Aspire, Kubernetes, OpenTelemetry + Jaegar,Elasticsearch,OAuth/OIDC/JWT ,Azure + Azure Devops CI/CD, AI/RAG + embedding + Semantic search + tool calling ,outbox , idempotency , resilience, concurrency, 

Project Structure
shopai-platform/
│
├── src/
│   ├── Services/
│   │   ├── Catalog/
│   │   ├── Basket/
│   │   ├── Ordering/
│   │   ├── Inventory/
│   │   ├── Payment/
│   │   └── AI/
│   │
│   ├── Gateway/
│   └── Frontend/
│
├── tests/
│   ├── Unit/
│   ├── Integration/
│   └── Architecture/
│
├── building-blocks/
│
├── deploy/
│   ├── docker/
│   ├── aspire/
│   └── kubernetes/
│
├── docs/
│   ├── architecture/
│   ├── decisions/
│   ├── api/
│   └── troubleshooting/
│
├── .github/
│   └── workflows/
│
├── README.md
├── docker-compose.yml
└── ShopAI.sln


Git strategy:
main
 │
 ├── develop
 │
 ├── feature/catalog-service
 ├── feature/order-service
 ├── feature/rabbitmq-messaging
 ├── feature/outbox
 ├── feature/ai-rag
 └── ...
