# 🚀 Boutique App with AI-Powered DevOps (AIOps)

> 🚀 Production-grade microservices application with **end-to-end DevOps + AIOps pipeline** deployed on AWS.

---

## 📌 Overview

This project showcases a **real-world DevOps architecture** integrated with **AIOps** to automate deployment, monitoring, and intelligent troubleshooting.

It demonstrates how modern systems evolve from:
**Code → CI/CD → Kubernetes → Observability → AI-driven insights**

---

## 🏗️ Architecture Diagram

flowchart LR

%% Developer Flow
A[👨‍💻 Developer] -->|Push Code| B[GitHub Repo]

%% CI/CD Pipeline
B -->|Trigger CI| C[GitHub Actions]
C -->|Build & Test| D[Docker Image]
D -->|Push Image| E[Container Registry]

%% GitOps Flow
C -->|Update Manifests| F[GitOps Repo]
F -->|Sync| G[ArgoCD]

%% Kubernetes Deployment
G -->|Deploy| H[AWS EKS Cluster]

%% Microservices
H --> I[Frontend - React]
H --> J[Backend - Node.js Services]
H --> K[Database - PostgreSQL]

%% Monitoring & Logging
H --> L[Prometheus]
H --> M[Grafana]
H --> N[Fluent Bit]

N --> O[CloudWatch Logs]

%% AIOps Layer
O --> P[AWS Bedrock - AIOps Agent]
P -->|Insights & Alerts| Q[DevOps Engineer]

%% Feedback Loop
Q -->|Fix / Improve| A


---

## ⚙️ Tech Stack

| Category       | Tools                       |
| -------------- | --------------------------- |
| Frontend       | React                       |
| Backend        | Node.js                     |
| Database       | PostgreSQL                  |
| Containers     | Docker                      |
| Orchestration  | Kubernetes (EKS)            |
| Infrastructure | Terraform                   |
| CI/CD          | GitHub Actions              |
| GitOps         | ArgoCD + Kustomize          |
| Monitoring     | Prometheus, Grafana         |
| Logging        | AWS CloudWatch + Fluent Bit |
| AIOps          | AWS Bedrock                 |

---

## 🔄 End-to-End Workflow

1. Developer pushes code to GitHub
2. GitHub Actions triggers CI pipeline
3. Docker images are built & pushed
4. ArgoCD syncs Kubernetes manifests
5. Application deployed on AWS EKS
6. Prometheus & Grafana monitor system
7. Logs sent to CloudWatch
8. AIOps agent analyzes anomalies & logs

---

## 📂 Repository Structure

├── docs/                     # System design & workflows
├── projects/
│   ├── boutique-microservices/   # Application services
│   ├── Infrastructure/           # Terraform (IaC)
│   └── aiops-assistant/          # AI Agent (Kira)
├── gitops/                  # ArgoCD + Kubernetes manifests
└── .github/workflows/       # CI/CD pipelines
```

---

 🤖 AIOps Capabilities
 
* 🔍 AI-powered log analysis
* ⚠️ Intelligent anomaly detection
* 🛠️ Root cause suggestions
* 📊 Operational insights using AWS Bedrock

---

🚀 Key Features

* End-to-end CI/CD automation
* Scalable Kubernetes-based microservices
* GitOps-driven deployments (ArgoCD)
* Infrastructure as Code (Terraform)
* AI-assisted DevOps (AIOps)
* Production-grade architecture

---

 🧪 Learning Outcomes

* Hands-on with **EKS, Terraform, ArgoCD, CI/CD**
* Deep understanding of **DevOps lifecycle**
* Implementation of **AIOps in real systems**
* Debugging distributed microservices

```

## 👨‍💻 Author

**Harsh Gupta**

* DevOps Engineer | Kubernetes | AWS | AIOps
* Focused on building scalable and intelligent cloud systems

---
