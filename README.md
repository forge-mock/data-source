## Pre-Installation process

Install needed tools:

1. Docker from [Docker Official Page](https://docs.docker.com/engine/install/). Any version above 27.4.0 will do.

## Installation process

1. Clone the repository to VM that should run db engines.
2. Create .env file and add environment variables for postgresql as in example:

```env
POSTGRES_USER=user
POSTGRES_PASSWORD=password
```

3. Navigate to folder's root and run:

```bash
docker compose up
```

## Run the project

1. Try to connect to https://localhost:5432/:
