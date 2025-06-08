# portfolio-nginx

## NGINX Reverse Proxy with Docker

This repository provides a production-ready reverse proxy solution using:

- `jwilder/nginx-proxy` for dynamic routing
- `letsencrypt-nginx-proxy-companion` for automatic HTTPS

## Usage

```bash
docker network create web
docker compose up -d
