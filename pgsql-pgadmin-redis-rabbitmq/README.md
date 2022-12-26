# PostgreSQL - PgAdmin - Redis - RabbitMQ

Common stack for backend development.

## Usage

Copy the .env.dist file to a new .env file and populate the file with credentials.

```shell
cp .env.dist .env
```

Create the new evnironment

```shell
docker compose up -d
```

## Ports

- 5432   - PostgrSQL
- 5050   - PgAdmin
- 6379   - Redis
- 5672   - RabbitMQ
- 15672  - RabbitMQ Management

## Web URLs

- [http://localhost:5050](http://localhost:5050) - PostgreSQL Management Portal
- [http://localhost:15672](http://localhost:15672) - RabbitMQ Management Portal
