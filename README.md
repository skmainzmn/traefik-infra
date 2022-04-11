# Traefik project
Proxy-server traefik for local development with databases (mariadb, mysql, redis and mongodb) and
minio (object storage compatible with S3).

## Installation
### 1. Clone the repository

```shell
git clone git@git.innoscripta.com:development/local-dbs.git
```

### 2. Set up the `.env` file

```shell
cp .env.example .env
```

### 3. Build and run services

```shell
docker-compose up --build -d
```

## Service using

| Service | Port       |
|---------|------------|
| MariaDB | 3308       |
| MySQL   | 3307       |
| Redis   | 6379       |
| MongoDB | 27017      |
| MinIO   | 9000, 9001 |
