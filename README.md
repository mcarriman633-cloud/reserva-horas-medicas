
# Reserva de horas médicas

Proyecto integrador de la asignatura DevOps.

## Descripción

Página web que simula un servicio de reserva de horas médicas.
El formulario es demostrativo y no almacena datos personales.

## Tecnologías utilizadas

- HTML y CSS
- Git y GitHub
- Docker Desktop
- Docker Compose
- Nginx

## Requisitos

- Git
- Docker Desktop
- Navegador web

## Instalación

git clone https://github.com/mcarriman633-cloud/reserva-horas-medicas.git

cd reserva-horas-medicas

## Ejecución

docker compose up -d --build

## Acceso al servicio

http://localhost:8080

## Verificación y monitoreo

docker compose ps

docker logs reserva-medica

docker stats --no-stream

## Detener el servicio

docker compose down

## Seguridad

- No publicar credenciales reales ni contraseñas.
- Utilizar .gitignore para excluir archivos sensibles.
- Utilizar .env.example como ejemplo de configuración.
- No ingresar datos reales de pacientes.
- Revisar los cambios antes de publicarlos en GitHub.

## Objetivo

Aplicar prácticas DevOps mediante el control de versiones,
la ejecución de contenedores y el monitoreo del servicio.
