# Day 3 — 2026-10-12

## What I did today
- Installed Docker + Compose on CachyOS
- Added myself to the docker group (no more sudo)
- Ran PostgreSQL + pgvector in a Docker container (behaviorlense_db)
- Connected FastAPI to Postgres via SQLAlchemy
- Built /ping-db endpoint — returns "connected"
- Verified the full stack works: FastAPI ↔ Postgres

## What I learned
- Docker containers are isolated boxes running a single service
- docker-compose.yml is a declarative config for multi-container setups
- Volumes preserve data across container restarts
- pgvector gives me vector search — needed for AI/RAG later
- The docker group grants root-equivalent access (worth knowing)



