# Keycloak

Keycloak is an open source Identity and Access Management solution aimed at modern applications and services. It makes it easy to secure applications and services with little to no code.

This repository contains  Besides that, it also contains files related to the [Authentication & Keycloak Course](https://plataforma.fullcycle.com.br/courses/3b8c4f2c-aff9-4399-a72a-ad879e5689a2/315/168/185/conteudos?), from FullCycle.

## Starting Keycloak Docker Container

To start a Keycloak Docker container, run the following command:

```bash
docker compose up -d --build
```

After start the container, you can access the Keycloak admin console at `http://localhost:8080/auth` with the following credentials:

- Username: `admin`
- Password: `admin`

To access the Mailhog web interface, go to `http://localhost:8026`. Any mail sent by Keycloak will be captured by Mailhog.
