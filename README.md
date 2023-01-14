# php-enviroment-8.2

## Enviroment para desarrollo con php 8.2

### Imagenes usadas
---
- **webdevops/php-nginx:8.2-alpine**
Esta fue usada en el Dockerfile

- **postgres:15.1-alpine**
Esta es la imagen de postgres

- **redis:7.0.7-alpine**
Imagen de redis

- **dpage/pgadmin4:latest**
Imagen del cliente administrador de base de datos
---

### Comandos para el deploy
- **docker compose build**
Para construir la imagen del Dockerfile

- **docker compose up -d**
Para montar los contenedores, el **-d** es para que ejecute el comando en segundo plano.

- **docker compose down**
Para desmontar los contenedores
