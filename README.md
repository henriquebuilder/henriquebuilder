# Luis Henrique — Senior Full Stack Engineer | Real-Time Systems · Edge Computing · AI Automation

Software engineer based in Brazil, building production systems across fintech, public safety, logistics, and Web3. I identify problems before writing code and stay in the system until it works correctly under failure — not just the happy path.

Open to remote opportunities.

---

## Projects

**[GuardianAlert](https://github.com/henriquebuilder/Guardianalert)**
Women's safety PWA — one-tap panic button that captures GPS, records 30s of audio as legal evidence, and sends SMS to emergency contacts in under 10 seconds. Disguise mode makes the app appear as a calculator so victims can open it undetected. Full security stack: httpOnly JWT, CSRF double-submit, TOTP/MFA, bcrypt cost 12, IP rate limiting, honeypot anti-bot. 100 active users in testing.

**[HR Screening AI](https://github.com/henriquebuilder/hr-screening-ai)**
AI hiring platform that conducts structured 8-question interviews via LLM, extracts candidate signals, and generates dual feedback — one report for the recruiter, one for the candidate. Built after noticing most applicants never hear back. 200 candidates processed in testing.

**[Bank Risk Platform](https://github.com/henriquebuilder/bank-risk-platform)**
Distributed fintech infrastructure focused on financial correctness under failure conditions. Double-entry bookkeeping, transactional outbox with Debezium CDC (PostgreSQL WAL → Kafka), pessimistic locking with `SELECT FOR UPDATE`, idempotent processing, Saga orchestration, and automated reconciliation pipelines. Java 21 + Spring Boot.

**[Logistics Real-Time Platform](https://github.com/henriquebuilder/toindo-express-platform-case-study)**
End-to-end logistics SaaS replacing polling with SSE — 97% reduction in backend requests across active drivers. State machine controls the full order lifecycle with strict transition validation. 3-stage photo pipeline (pickup, delivery, proof-of-delivery) with automated state transitions. Event sourcing for full audit trail. In production managing real operations.

**[Pozzer DePIN Protocol](https://github.com/pozzer-labs/pozzer-blockchain)**
Web3 infrastructure protocol with EVM signature-based wallet auth (nonce flow — no passwords, no email), multi-chain support (Ethereum, Polygon, BSC), mission-based gamification, and Solidity smart contracts for on-chain reward distribution. 1,000 testnet users. Live at [pozzer.io/explorer](https://pozzer.io/explorer).

**[CryptoPay — Fintech](https://github.com/henriquebuilder/Fintech-Cryptopay)**
Hybrid crypto/fiat platform with multi-asset wallet (BTC, ETH, USDT, BNB), crypto-to-PIX conversion with real-time exchange rate feeds and async settlement orchestration, and a service marketplace. 2000 active users over 4 years.

---

## Stack

```
Languages    TypeScript · JavaScript · Python · Java · Solidity
Frontend     React · Tailwind CSS · PWA
Backend      Cloudflare Workers · Hono · FastAPI · Spring Boot · Node.js
Database     Cloudflare D1 · Cloudflare R2 · PostgreSQL
Real-Time    SSE · event-driven · Kafka
AI           LLMs · LangGraph · CrewAI · LangChain · RAG · n8n · Groq
Web3         Ethers.js · Web3Modal · EVM wallet auth · multi-chain · Solidity
Security     JWT (httpOnly) · CSRF protection · bcrypt · TOTP/MFA · rate limiting · honeypots
Infra        Docker · Kafka · Redis · Debezium CDC · OpenTelemetry
```

---

## How I work

---
I use AI as an accelerator — Cursor, Claude, Copilot — and take full ownership of the architecture, security decisions, and tradeoffs behind everything I ship. I go after the bugs, study the failure modes, and understand the system well enough to evolve it when things break in production.


## Currently

Implementing distributed ledger services in Java 21 + Spring Boot
Developing advanced AI-powered recruitment tools using multi-agent workflows (LangGraph)
Expanding GuardianAlert toward municipal partnerships and NGO pilots
Studying distributed systems: consensus, replication, partition tolerance

---

📍 Brazil · Remote
🔗 [henriquebuilder.space](https://henriquebuilder.space) · [LinkedIn](https://br.linkedin.com/in/luis-henrique-da-silva-cunha-89bba8124)
