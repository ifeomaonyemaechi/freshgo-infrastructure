# 🚚 FreshGo Delivery — Cloud Infrastructure

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Terraform](https://img.shields.io/badge/IaC-Terraform-purple?logo=terraform)
![Linux](https://img.shields.io/badge/OS-Linux-yellow?logo=linux)
![Status](https://img.shields.io/badge/Status-In%20Progress-blue)

## About FreshGo Delivery

FreshGo Delivery is a fictional cloud-native logistics platform used as a
production-grade infrastructure case study. It simulates the real-world
challenges of designing, deploying, and securing scalable cloud infrastructure
for a high-availability last-mile delivery system operating across multiple
regions.

This repository documents the full infrastructure build — from VPC design to
CI/CD automation — built entirely on AWS following industry best practices.

---

## Business Problem

FreshGo Delivery needed a cloud infrastructure that could:

- Handle high volumes of delivery orders with zero downtime
- Scale automatically during peak delivery hours
- Secure customer and delivery data across all services
- Deploy application updates rapidly without service interruption
- Monitor infrastructure health and respond to incidents in real time

---

## Infrastructure Overview

| Layer | Technology | Status |
|---|---|---|
| Cloud Platform | AWS | ✅ Active |
| Networking | AWS VPC, Subnets, Route Tables, Security Groups | 🔄 In Progress |
| Identity & Access | AWS IAM, Organizations, Identity Center | 🔄 In Progress |
| Infrastructure as Code | Terraform | 🔜 Upcoming |
| CI/CD Pipeline | GitHub Actions + AWS CodePipeline | 🔜 Upcoming |
| Containerization | Docker + Amazon ECR | 🔜 Upcoming |
| Monitoring & Alerting | Amazon CloudWatch | 🔜 Upcoming |

---

## Repository Structure
```
freshgo-infrastructure/
├── docs/          # Architecture decisions and technical write-ups
├── networking/    # VPC design, subnets, security groups
├── terraform/     # Infrastructure as Code configurations
├── cicd/          # GitHub Actions workflows and pipeline configs
└── monitoring/    # CloudWatch dashboards, alerts, and logging
```

---

## Architecture Principles

- **Security First** — Least privilege IAM, encrypted storage, private subnets
- **High Availability** — Multi-AZ deployments, auto scaling, load balancing
- **Cost Optimisation** — Right-sized resources, lifecycle policies, cost tags
- **Automation** — Everything provisioned as code, no manual console clicks
- **Observability** — Full logging, metrics, and alerting across all services

---

## About This Project

This infrastructure is being built as part of a structured DevOps and Cloud
Security training programme. Every component is documented, version-controlled,
and explained as if deployed in a real production environment.

**Trainee:** Ifeoma Onyemaechi
**Focus:** DevOps | Cloud Security | AWS | Terraform | CI/CD
**Location:** South Africa
**LinkedIn:** [Connect with me](#) ← replace with your LinkedIn URL

---

> *"Every concept learned is applied, documented, and explained clearly —
> as if already working in a production environment."*
