# Staybooking

Staybooking is a full-stack booking application.

## Project structure

- `src/`, `build.gradle`: Spring Boot backend
- `frontend/`: React frontend
- `compose.yaml`: local PostGIS database

## Backend

Configure the required environment variables in a local `.env` file, then run:

```bash
docker compose up -d
./gradlew bootRun
```

The backend runs on `http://localhost:8080` by default.

## Frontend

```bash
cd frontend
npm install
npm start
```

Create an optimized frontend build with:

```bash
npm run build
```

Local credentials and environment files are intentionally excluded from Git.
