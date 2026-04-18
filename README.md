# HR Chatbot Architecture: POC to Enterprise Product

This repository showcases the architectural evolution of a **Multi-Agent Retrieval-Augmented Generation (RAG) Chatbot** designed for the Human Resources domain at HTI Group. 

🌐 **Live Portfolio:** [https://maver1ch.github.io/hr-rag-chatbot-architecture/](https://maver1ch.github.io/hr-rag-chatbot-architecture/)

## Overview
The architecture diagrams map out the system's journey from an initial Proof of Concept (POC) to a highly scalable, production-ready enterprise solution.

### Phase 1: Proof of Concept (POC)
- **High-Level System Architecture:** Core API interactions bridging the frontend UI with AI knowledge engines.
- **Multi-Agent Router (ReAct):** The intelligent routing core that classifies queries and orchestrates specialized sub-agents for tasks like policy lookup and payroll inquiries.

### Phase 2: Enterprise Product Level
- **AWS Cloud Migration:** High-availability deployment on AWS leveraging managed services, container orchestrations (EKS/ECS), and multi-AZ VPC isolation.
- **Serverless Ingestion Pipeline:** An event-driven, fully scalable data ingestion flow utilizing serverless computing to process enterprise documents cost-effectively.

---
*Designed & Architected by System Engineering | HTI Group.*
