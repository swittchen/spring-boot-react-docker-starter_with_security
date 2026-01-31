# Smart Task Manager (SMT)

Monorepo containing:
- `backend/` Spring Boot (Java 21, JPA, Security)
- `frontend/ui/` React + Vite

## Prerequisites
- Docker + Docker Compose

## Run database only
```bash
docker compose up -d db
```

## Run backend + database
```bash
docker compose up -d --build
```
- Backend runs on: http://localhost:8080

## Stop
```bash
docker compose down

```

## Logs
```bash
docker compose logs -f backend
docker compose logs -f frontend

```


