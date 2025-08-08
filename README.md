# N8N
Services:

- n8n: automation platform
- redis: nosql database
- postgres: relational database
- traefik: reverse proxy with TLS support

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://gitgithub.com/kris-smarthome/docker-n8n.git
cd docker-n8n
nano .env
docker compose up -d
```

> [!NOTE]
> This stack incldes traefik, create the traefik network before deploying this stack: `docker network create -d bridge traefik`