# TP06 — Dockerfile avanzado y Docker Compose

App de notas compuesta por frontend, backend y base de datos PostgreSQL usando Docker Compose.

## Servicios

- frontend: Nginx sirviendo la interfaz web.
- backend: API Flask.
- db: PostgreSQL 16 Alpine.

## Levantar el stack

```bash
sudo docker compose up -d
