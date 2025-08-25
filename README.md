# Hi, I'm Vitalii — Senior Full-Stack Engineer

I build **streaming-first backends** and **mobile apps** that are easy to operate: clear APIs, solid tests, and dashboards that tell the truth. Lately I’ve focused on **LLM-powered features** with measurable latency, cost, and reliability.

- **Backend:** Python (FastAPI, AsyncIO, Pydantic v2), SQLAlchemy 2.0, Celery, PostgreSQL, Redis  
- **AI:** OpenAI API, pragmatic **RAG** (Qdrant/pgvector), **MLflow** experiments, **local models** via **Ollama / llama.cpp / vLLM**  
- **Ops:** Docker, GitHub Actions, **Prometheus + Grafana**, **OpenTelemetry** tracing, Sentry  
- **Mobile:** Flutter (Dart, BLoC/Cubit, Provider, auto_route), Android/Kotlin (incl. **BLE/GATT**)

---

## What I’m building now — **RAGline**
A public PoC that shows senior backend practices + LLM orchestration in one repo.

- **FastAPI** service with **JWT multi-tenancy**, typed contracts, and **SSE/WebSocket** streaming  
- **Idempotent writes**, **outbox → Redis Streams** fan-out, retries, DLQ  
- **Observability first:** route histograms, cache hit ratio, stream lag; **OTel traces** across API → DB → Redis → worker  
- **/chat orchestration** with tool calls and **RAG**; switch to **local models** by setting `OPENAI_API_BASE`  
- **CI/CD** with lint/type/tests + ownership guards; small PRs, fast merges

> Why it matters: you can see **p50/p95** numbers, traces, and the exact code that keeps releases predictable.

---

## Recent highlights
- **Creative Coach (FastAPI + Celery):** streaming insights over WebSockets; **multi-model routing cut serving cost ~98%** with 50+ tracked metrics in MLflow.  
- **Flutter UI Library Lead:** 120+ reusable widgets adopted across apps; feature lead time improved by ~40%.  
- **Android BLE (sports insole):** full GATT profile (scan/bond, R/W, notify), background reconnection, field diagnostics with nRF Connect.

---

## Tech I use (and enjoy)
**Python:** FastAPI, AsyncIO, Pydantic v2, SQLAlchemy 2.0, Celery  
**Data/Infra:** PostgreSQL, Redis, Docker, GitHub Actions  
**AI/LLM:** OpenAI API, RAG with Qdrant/pgvector, MLflow; local models via **Ollama / llama.cpp / vLLM**  
**Observability:** Prometheus, Grafana, OpenTelemetry, Sentry  
**Mobile:** Flutter, Dart (BLoC/Cubit, Provider, auto_route), Android/Kotlin (BLE)  
**Cloud (used/familiar):** AWS (Lambda, AppSync, DynamoDB), GCP (GKE/Cloud Run), Firebase

---

## How I work
- **Contract-first:** OpenAPI & event schemas before code  
- **Metrics-first:** set SLOs, watch p95, fix root causes, add a safeguard  
- **CI discipline:** tests, lint, types, security checks on every PR  
- **Small batches:** feature flags, frequent releases, clean rollbacks  
- **Leadership:** led **3 teams (2–6 devs)**; set review/testing standards; mentor kindly, ship steadily

---

## Contact
- **Email:** serbyn.vitalii@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/vitalii-serbyn-b517a083/  
- **Portfolio:** https://serbyn.pro

---

## GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vitamin33&hide=contribs&theme=merko" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vitamin33&theme=merko&layout=compact" alt="Top Languages" />
</div>

## Streak
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vitamin33&theme=merko" alt="Streak Stats" />
</div>

## ☕️ Support
<div align="center">
  <a href="https://www.buymeacoffee.com/futuristicCowboy" target="_blank">
    <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" />
  </a>
</div>
