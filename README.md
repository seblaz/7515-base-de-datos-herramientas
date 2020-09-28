# Herramientas para Base de datos (FIUBA)

Imágenes de [Docker](https://docker.io/) para trabajar en la materia Base de datos de la FIUBA. Se incluye:

- [PostgreSQL 13.0](https://www.postgresql.org/)
- [pgAdmin 4.26](https://www.pgadmin.org/)

## Comandos disponibles

#### `docker-compose up -d`

Inicia los servicios de Docker.

**Postgresql** se expone en el puerto por defecto (5432)

**pgAdmin** se puede acceder desde [localhost:8080](http://localhost:8080)



Adicionalmente se puede acceder al CLI de los servicios con `docker-compose exec <servicio> bash` (ej: `docker-compose exec postgres sh`).