# Dev Traefik

Simple Traefik instance that can be used in development environment.

    docker network create --driver=overlay proxy --attachable
    CF_DNS_EMAIL=user@example.com CF_DNS_API_TOKEN=xxx docker stack deploy traefik -c docker-compose.yml