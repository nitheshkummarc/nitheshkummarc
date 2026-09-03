Hi, I'm Nitheshkummar👋

Backend Engineer focused on AI-native systems — where the LLM proposes and deterministic systems decide.
I build reliable backend systems, secure retrieval pipelines, and agentic workflows with hard boundaries around what the model is allowed to do.

## 🚀 Featured Projects

### 🤖 [Revora — Agentic Payment Failure Recovery](https://github.com/nitheshkummarc/revora)
The model recommends recovery actions; a deterministic policy engine validates every recommendation before execution. Model output is a suggestion, never an authority.
A deterministic resolution layer reconciles late, duplicated, contradictory, and out-of-order webhook events before AI reasoning runs. Execution is only considered successful after system state is verified against the intended outcome.

**Tech:** Python • FastAPI • Pydantic • Gemini/Groq

### 🔒 [Aegis — Enterprise RAG with Transactional RBAC](https://github.com/nitheshkummarc/Aegis-Enterprise-RAG-with-Transactional-RBAC)
RAG system where permission checks run inside the same SQL query as vector retrieval, so unauthorized document chunks never reach the LLM. Uses role-aware partial HNSW indexes across three clearance levels, verified against live PostgreSQL EXPLAIN plans.
Validated with a 105-test suite and instrumented end-to-end with Langfuse.

**Tech:** Python • FastAPI • PostgreSQL + pgvector • Next.js • Celery/Redis • Langfuse

### 🏗️ [WorkLens](https://github.com/nitheshkummarc/worklens)
Deterministic, explainable candidate-ranking engine that evaluates 100,000 candidate profiles against a job specification in under 2 minutes on a single CPU core, with zero runtime network dependencies.

**Tech:** Python • Pydantic • Docker

### 📊 [Spark Failure Propagation & Root-Cause Analytics](https://github.com/nitheshkummarc/spark-failure-propagation-root-cause-analytics)
Distributed root-cause analysis platform for Apache Spark — reconstructs execution DAGs from event logs, traces failures through Reverse BFS, and classifies failure scenarios from runtime telemetry with 88.2% accuracy.

**Tech:** Scala • Apache Spark • PySpark • Hadoop (HDFS/YARN) • Docker

### 📅 [PlanPal](https://github.com/nitheshkummarc/planpal)
Community-driven event-management platform with JWT authentication, role-based authorization, event participation workflows, and a PostgreSQL-backed REST API.

**Tech:** Python • React • Flask • PostgreSQL • SQLAlchemy • JWT • Tailwind CSS

## 💻 Engineering Focus
Backend Engineering • AI Agent Systems & Guardrails • RBAC / Secure Retrieval • Distributed Systems • Software Architecture • AI Reliability

## 📫 Connect
📧 Email: [nitheshkummarni@gmail.com](mailto:nitheshkummarni@gmail.com)

💼 LinkedIn: https://linkedin.com/in/nitheshkummar
