
<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/storybook-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/webpack-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/graphql-icon.svg" alt="icon" width="52" height="52" /></div>

<!--START_SECTION:activity-->
1. ❌ Merged PR [#8](undefined) in [tamirazrab/parley](https://github.com/tamirazrab/parley)
2. 💪 Opened PR [#8](undefined) in [tamirazrab/parley](https://github.com/tamirazrab/parley)
3. ❌ Merged PR [#7](undefined) in [tamirazrab/parley](https://github.com/tamirazrab/parley)
4. 💪 Opened PR [#7](undefined) in [tamirazrab/parley](https://github.com/tamirazrab/parley)
5. ❌ Merged PR [#6](undefined) in [tamirazrab/parley](https://github.com/tamirazrab/parley)
<!--END_SECTION:activity-->

![:swiss](https://count.getloli.com/@swiss?name=swiss&theme=random&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto&num=6921)

# Tambir Azrab

**Backend Engineer** building scalable systems for fintech and high-traffic platforms.

## 👋 What I Do

I specialize in **backend infrastructure** that handles real-world scale — the kind where a production incident doesn't just break a feature, it impacts millions of users and millions of dollars in transactions.

For the past 4 years, I've worked on:
- **Fintech systems** processing 2M+ monthly transactions for 15M+ users (JazzCash)
- **Event-driven architectures** using Kafka, MongoDB, PostgreSQL, Redis
- **Performance-critical services** where 60-second batch jobs need to run in under 10 seconds
- **Cost-optimized deployments** (modular monoliths on Azure Functions @ <$50/month)

## 🛠️ Tech Stack

**Core:** Node.js, TypeScript, Express, NestJS, PostgreSQL, MongoDB, Redis, Kafka, Docker  
**Familiar:** AWS (EC2/S3/Lambda), OpenShift, Kubernetes, RabbitMQ, GraphQL, Terraform  
**Learning:** Distributed tracing (OpenTelemetry), service mesh (Istio), chaos engineering

## 🎯 What Problems I Solve

- Scaling backend services under exponential traffic growth
- Eliminating production incidents through systematic re-architecture
- Optimizing database queries and batch jobs for high-volume workloads
- Designing event-driven systems with transactional guarantees
- Building cost-effective infrastructure without sacrificing reliability

## 🌟 Open Source

Contributor to [**Pepr**](https://github.com/defenseunicorns/pepr) — Kubernetes policy-as-code framework  
→ Fixed circular dependencies in TypeScript codebase  
→ Refactored admission lifecycle validation logic  
[View contributions →](https://github.com/defenseunicorns/pepr/pulls?q=is%3Apr+author%3Atamirazrab)

## 📫 Let's Connect

- **Email:** tamirazrab@gmail.com
- **LinkedIn:** [linkedin.com/in/tamirazrab](https://linkedin.com/in/tamirazrab)
- **Location:** Rawalpindi, Pakistan (Open to remote/relocation)

---

*Looking for backend-heavy roles in fintech, payments, infrastructure, or high-scale consumer products. If your system processes millions of transactions and needs bulletproof reliability, let's talk.*
```

---

### 🗂️ **Repository Ideas to Create**

#### **1. `transaction-orchestrator`**
**What It Demonstrates:** Distributed transactions, event sourcing, Saga pattern

**Description:**  
Production-ready implementation of Saga orchestration pattern for distributed transactions across multiple services (payment, inventory, notification). Includes compensating transactions, idempotency handling, and event replay.

**Tech Stack:** Node.js, TypeScript, Kafka, PostgreSQL, Redis (idempotency), Docker Compose  
**Key Features:**
- Two-Phase Commit coordinator
- Compensating transaction rollback
- Idempotency via Redis distributed locks
- Event sourcing for audit trails
- Health checks and circuit breakers

**Why:** Directly mirrors your JazzCash bundle subscription work, shows advanced architectural patterns

---

#### **2. `high-scale-batch-processor`**
**What It Demonstrates:** Performance optimization, streaming, memory management

**Description:**  
Benchmarking framework comparing batch processing strategies for million-record datasets: in-memory vs. cursor streaming vs. worker pools. Includes heap profiling, performance metrics, and trade-off analysis.

**Tech Stack:** Node.js, MongoDB, PostgreSQL, Bull (job queues), Prometheus metrics  
**Key Features:**
- Cursor-based streaming implementation
- Worker pool parallelization
- Memory profiling snapshots
- Grafana dashboards for metrics
- Configurable batch sizes and concurrency

**Why:** Validates your cashback scheduler optimization story, demonstrates database expertise

---

#### **3. `cost-optimized-modular-monolith`**
**What It Demonstrates:** Architectural decision-making, DDD, cloud cost awareness

**Description:**  
Reference architecture for NestJS modular monolith with explicit bounded contexts, designed for Azure Functions deployment. Includes migration path to microservices with service extraction guide.

**Tech Stack:** NestJS, Azure Functions, MongoDB, Terraform, Docker  
**Key Features:**
- Bounded context modules (auth, orders, inventory, notifications)
- In-process event bus with future Kafka migration
- Shared kernel vs. bounded context isolation
- Cost comparison calculator (monolith vs. microservices)
- Deployment automation (Terraform)

**Why:** Showcases your Takmil architecture, demonstrates business acumen

---

#### **4. `fintech-api-patterns`**
**What It Demonstrates:** Payment systems knowledge, idempotency, security

**Description:**  
Collection of production-grade API patterns for financial systems: idempotent payment processing, webhook retry mechanisms, double-entry bookkeeping, reconciliation workflows.

**Tech Stack:** Node.js, PostgreSQL (with transactions), Redis (distributed locks), Stripe webhooks  
**Key Features:**
- Idempotency key enforcement
- Webhook signature verification
- Double-entry ledger implementation
- Reconciliation job scheduler
- Rate limiting and circuit breakers

**Why:** Positions you as fintech specialist, shows payment domain expertise

---

#### **5. `observability-starter`**
**What It Demonstrates:** Production readiness, SRE mindset, monitoring

**Description:**  
Observability stack for Node.js microservices: structured logging, distributed tracing (OpenTelemetry), metrics (Prometheus), alerting (Grafana). Includes SLO/SLI definitions and dashboard templates.

**Tech Stack:** Express, OpenTelemetry, Prometheus, Grafana, Loki, Jaeger  
**Key Features:**
- Auto-instrumentation setup
- Trace context propagation
- Custom metrics (RED method)
- Pre-built Grafana dashboards
- Alerting rules (latency, error rate)

**Why:** Fills observability gap in your CV, shows production maturity

---

#### **6. `event-driven-e-commerce`**
**What It Demonstrates:** Kafka expertise, CQRS, event sourcing

**Description:**  
Event-sourced e-commerce backend using Kafka for command/event separation. Demonstrates CQRS, event replay, read model projections, and eventual consistency handling.

**Tech Stack:** Node.js, Kafka, PostgreSQL (write), MongoDB (read models), Docker  
**Key Features:**
- Command handlers with event publishing
- Event consumer read model projections
- Snapshot strategy for event replay
- Saga coordinator for order fulfillment
- Eventual consistency conflict resolution

**Why:** Proves event-driven architecture depth, shows advanced Kafka usage

---

### 🔧 **Suggestions for Existing Repos** (If They Exist)

Based on CV mentions, if you have existing projects:

**Canvastra / Portico / Zentra:**
1. **Add Production Readiness:**
   - GitHub Actions CI/CD (linting, tests, Docker build)
   - Comprehensive README with architecture diagrams
   - API documentation (Swagger/OpenAPI)
   - Deployment guides (Docker Compose, cloud deployment)

2. **Showcase Technical Depth:**
   - Add `/docs` folder with:
     - System architecture diagram (C4 model)
     - Database schema diagrams
     - API flow diagrams
     - Decision records (ADRs)
   - Performance benchmarks (load testing results)
   - Security considerations document

3. **Demonstrate Best Practices:**
   - Pre-commit hooks (linting, type checking)
   - Conventional commit messages
   - Branch protection rules
   - Issue/PR templates
   - Contributing guidelines

---

## PART 4: WHAT'S MISSING (GAP ANALYSIS)

### 🚨 **Critical Keywords Missing for Your Level**

#### **Technical Gaps:**
```
HIGH PRIORITY (Add to LinkedIn/Resume):
- Distributed Tracing (Jaeger, Zipkin, OpenTelemetry)
- APM (Application Performance Monitoring)
- SLI/SLO/SLA definitions
- Circuit Breaker pattern
- Rate Limiting strategies
- API Gateway (Kong, Traefik)
- Service Mesh (Istio, Linkerd)
- Database Replication/Sharding
- Query Optimization/EXPLAIN analysis
- Connection Pooling
- Secret Management (Vault, AWS KMS)
- Horizontal Pod Autoscaling
- Blue-Green Deployments
- Canary Releases

MEDIUM PRIORITY:
- gRPC in production
- GraphQL Federation
- WebSocket scaling (Socket.io clustering)
- CDC (Change Data Capture)
- Multi-region deployment
- Disaster Recovery planning
- Chaos Engineering (basic)
```

#### **Fintech-Specific Gaps:**
```
- PCI-DSS compliance exposure
- Fraud detection systems
- Payment gateway integrations (Stripe, PayPal internals)
- Reconciliation workflows
- Double-entry bookkeeping
- Financial reporting/audit trails
- Regulatory compliance (mention if you have ANY exposure)

<!-- ![Self Help](https://user-images.githubusercontent.com/74038190/212284094-e50ceae2-de86-4dd6-9f9c-a3ebcb3ede9e.gif) -->
