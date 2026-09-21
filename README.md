# Sevian Arivyartha

**Software Engineer · Jakarta, Indonesia (UTC+7)**

Software engineer with 4+ years in Rails, Go, Python, and AI workflows. I own production systems end to end: design, release, and the incident afterwards. I find root causes rather than symptoms and build async systems that fail safely.

Currently at **[Luce](https://www.luce.sg/)**, a Singapore home-services platform.

## What I Work On

- **Background jobs that are safe to run twice**: retries, locks, and idempotent writes, so a crashed worker never charges anyone double.
- **Money code**: wallets, invoices, and payment matching, where the totals have to add up every time.
- **LLM features that hold up in production**: guardrails, fallbacks, and a clean handoff to a human when the model is unsure.
- **Slow things made fast**: pulled a core library out of a Rails monolith into a standalone Go service and halved report generation time.
- **Incidents**: I trace a failure to its root cause, fix it, and write the runbook. At one job those runbooks cut resolution time by about 90%.

## How I Use AI

AI assistants are a real part of how I work. They shorten the loop between idea and prototype and take care of the mechanical parts. These are the rules I hold them, and myself, to.

1. **Think before coding.** State the assumptions. Ask instead of guessing.
2. **Read before you write.** Learn the callers and the conventions, then follow them.
3. **Test first.** A failing test, then the code. The test has to show why the behaviour matters.
4. **Simplicity first.** The smallest change that solves the problem, and nothing nobody asked for.
5. **Fail loud.** Never say "done" when something was skipped or never verified.

Used well, they raise the ceiling of what a single engineer can ship.

## Open Source

- **[redacted](https://github.com/svn-arv/redacted)** (Go): secrets guardrail for AI coding assistants. Detects and redacts credentials before tool output reaches external APIs, using pattern matching and entropy-based scoring. Site: [redacted.my.id](https://redacted.my.id)
- **[event_timeline](https://github.com/svn-arv/event_timeline)** (Ruby gem): records model state changes as a queryable audit trail for traceability and debugging.

## Stack

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=rubyonrails&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

## Elsewhere

- [sevian.my.id](https://sevian.my.id/)
- [LinkedIn](https://linkedin.com/in/sevian-arivyartha)
