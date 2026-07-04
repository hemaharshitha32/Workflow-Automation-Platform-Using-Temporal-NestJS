# Workflow Automation Platform Using Temporal & NestJS

## Overview

**Workflow Automation Platform Using Temporal & NestJS** is a scalable full-stack platform designed for building reliable and fault-tolerant distributed applications. The project combines **Temporal Workflow Orchestration**, **NestJS** microservices, **React Router**, and **Turborepo** to simplify the development of long-running business workflows while ensuring durability, consistency, and automatic recovery from failures.

Unlike traditional request-response applications, this platform manages complex business processes through durable workflows that can execute for extended periods, recover automatically from failures, and coordinate communication between multiple services.

---

## Motivation

Modern distributed systems face several challenges:

- Maintaining workflow state
- Service failures
- Retry management
- Long-running business processes
- Event-driven communication
- Scalability across multiple services

This project addresses these problems by integrating **Temporal** as the workflow engine with **NestJS** microservices and a modern **React** frontend.

---

# 🏗 Architecture

<p align="center">
  <img src="C:\Users\hemah\Downloads\ChatGPT Image Jul 4, 2026, 05_58_12 PM.png" alt="Workflow Automation Platform Architecture" width="900"/>
</p>

---

## Features

###  Workflow Orchestration

- Durable workflow execution
- Retry policies
- Automatic failure recovery
- Long-running workflow support
- Scheduled workflows
- Human-in-the-loop workflows

###  Microservices

- NestJS-based services
- REST API communication
- Modular architecture
- Independent deployment
- Service isolation
- Horizontal scalability

###  Developer Experience

- Turborepo monorepo
- Automatic service generators
- Interactive CLI
- Hot reload
- Shared libraries
- Type-safe development

###  Deployment

- Docker Compose
- PostgreSQL integration
- Temporal Server
- Service orchestration
- Environment configuration
- Easy local setup

---

#  Technology Stack

## Frontend

- React Router
- TypeScript

## Backend

- NestJS
- Node.js
- Temporal SDK

## Database

- PostgreSQL

## DevOps

- Docker
- Docker Compose

## Monorepo

- Turborepo
- PNPM

## Tools

- Git
- GitHub
- Storybook

---

#  Key Capabilities

### Durable Execution

Ensures workflows continue executing even after server crashes or restarts without losing progress.

### Fault Tolerance

Automatically retries failed activities using configurable retry policies.

### State Management

Maintains workflow state for days, weeks, or even months without requiring custom persistence logic.

### Scalability

Supports multiple independent microservices that can scale horizontally based on workload.

### Workflow Monitoring

Provides complete execution history, status tracking, and debugging through the Temporal UI.

### Event-Driven Processing

Supports asynchronous communication between services using signals, updates, and activities.

---

#  Example Use Cases

- Order Processing Systems
- User Registration Workflows
- Payment Processing
- Inventory Management
- Email Notification Pipelines
- Approval Workflows
- Data Processing Pipelines
- Batch Job Automation

---

#  Folder Structure

```text
workflow-automation-platform/
│
├── apps/
│   ├── web/
│   ├── auth-service/
│   ├── order-service/
│   ├── product-service/
│
├── packages/
│
├── docker-compose.yml
├── turbo.json
├── package.json
└── README.md
```

---

#  Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/workflow-automation-platform.git

# Navigate to the project
cd workflow-automation-platform

# Install dependencies
pnpm install

# Configure environment
cp .env.example .env

# Start required services
docker-compose up -d

# Run the application
pnpm dev
```

---

#  Future Enhancements

- Kubernetes deployment
- CI/CD pipeline
- Redis caching
- Kafka integration
- OAuth authentication
- API Gateway
- Prometheus & Grafana monitoring
- Distributed tracing
- Load balancing

---




This project is released under the **MIT License**.

---

⭐ **If you found this project useful, don't forget to give it a star!**
