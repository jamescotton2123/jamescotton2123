# 👋 I'm James Cotton

Backend engineer and alternative-investments operations professional (Series 65) 
building production Python systems for regulated financial workflows.

By day I run investor onboarding, KYC, and fund operations at a wealth management 
firm. I deployed automation adopted by 8 advisors across 6 active fund closings — 
cutting per-investor processing from ~25 minutes to under 5 minutes across 99+ 
investors per closing.

## Current Project

### [Altvio — Alternative Investments Operations Platform](https://github.com/jamescotton2123/altvio)

Production-equivalent platform built in parallel to solving the same problems live 
at work. Not a tutorial project — a full backend system for the workflows I operate 
every day.

**What it implements:**

- Multi-tenant FastAPI + Postgres/Supabase backend with `firm_id` RLS isolation, 
  120 REST endpoints, and a hash-chained tamper-evident audit ledger
- 9 agentic AI workflows: NL→SQL via allowlisted RPCs, GPT-4o Vision for 
  KYC/sub-doc/wire extraction, intake parsing, and human-in-the-loop pending-change queues
- Event-driven integrations: DocuSign JWT + Connect webhooks, Microsoft Graph 
  mailbox subscriptions, SharePoint file flows, Orion NAImport export
- Institutional-grade reliability: HMAC webhook verification, idempotent event 
  deduplication, bcrypt API-key rotation, tenacity retry wrappers, structured JSON logging
- Role-scoped access patterns for ops, advisors, investors, traders, and client 
  associates using firm-scoped headers, hashed API keys, portal tokens, and webhook 
  signature validation

## Technical Stack

| Layer | Stack |
|-------|-------|
| Backend | Python, FastAPI, Pydantic, SQL |
| Data | Postgres, Supabase, RLS, schema migrations |
| AI | OpenAI GPT-4o, Anthropic Claude, function calling, Vision |
| Integrations | DocuSign, Microsoft Graph, SharePoint, Orion NAImport |
| Reliability | pytest, tenacity, APScheduler, structured logging, Docker |

## Connect

[LinkedIn](https://linkedin.com/in/jamescotton23)
