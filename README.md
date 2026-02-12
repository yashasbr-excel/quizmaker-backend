# Quizmaker Backend

Skeleton Spring Boot backend for the Quizmaker app.

## Tech stack

- **Java**: JDK 21
- **Framework**: Spring Boot 3.5.10
- **Database**: HSQLDB (in-memory)

## Build and run

```bash
./mvnw spring-boot:run
```

Or with Maven installed:

```bash
mvn spring-boot:run
```

The server starts on **http://localhost:8080**.

## API

- **GET /api/bff/welcome** — Returns a JSON welcome message: `{ "message": "Welcome to Quizmaker!" }`

## Configuration

- `application.properties` configures HSQLDB (in-memory), JPA, and CORS for the frontend dev server (port 5173).
