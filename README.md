# TaskFlow Frontend

Interfaz web de TaskFlow, una aplicación para gestionar proyectos y tareas en equipos pequeños. Este repositorio tiene solo el frontend. El backend está en [taskflow-backend](https://github.com/piero2607/tasflow-backend).

Es el proyecto final del ciclo de Desarrollo de Aplicaciones Web (DAW), curso 2026-2027.

## Estado

En desarrollo.

## Funcionalidades previstas

- Registro e inicio de sesión.
- Creación y gestión de proyectos, con miembros.
- Tareas con responsable, prioridad, fecha límite y estado (pendiente, en proceso o completada).
- Tablero Kanban para ver el progreso de cada proyecto.
- Diseño adaptable a distintos dispositivos.

## Tecnologías

- Angular
- TypeScript
- HTML5
- SCSS

## Requisitos

- Node.js (versión LTS) y npm
- Angular CLI
- El backend en marcha (ver su repositorio)

## Instalación y ejecución

```bash
git clone https://github.com/USUARIO/taskflow-frontend.git
cd taskflow-frontend
npm install
ng serve
```

La aplicación se abre en http://localhost:4200.

## Configuración

La URL de la API se define en el archivo de entorno del proyecto. En desarrollo apunta al backend local:

```
http://localhost:8080/api
```

Cámbiala si el backend corre en otro puerto o en otro servidor.

## Equipo

- Mar Bellver Alecreu (frontend)
- Piero Yovera Anaya (backend, en [taskflow-backend](https://github.com/piero2607/tasflow-backend))
