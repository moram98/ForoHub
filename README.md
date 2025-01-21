# ForoHub System

ForoHub es una plataforma basada en Spring Boot diseñada para crear, gestionar y participar en foros educativos. Este proyecto implementa un sistema robusto y seguro para usuarios, temas, cursos y respuestas.

---

## **Características**
- **Gestión de Usuarios**: Autenticación y autorización con JWT.
- **Gestión de Foros**: Creación y visualización de temas y respuestas.
- **Gestión de Cursos**: Asociación de cursos con temas y categorías.
- **Documentación de la API**: Generada con Swagger.
- **Seguridad**: Implementación de roles y permisos con Spring Security.

---



## **Tecnologías Utilizadas**
- **Lenguaje**: Java 17
- **Framework Principal**: Spring Boot
- **Seguridad**: Spring Security, JWT
- **Acceso a Datos**: Spring Data JPA, Hibernate
- **Base de Datos**: MySQL
- **Documentación**: SpringDoc OpenAPI (Swagger)

## **Endpoints Principales**

| Método | Endpoint                  | Descripción                            |
|--------|---------------------------|----------------------------------------|
| POST   | `/auth/login`             | Autenticar un usuario.                 |
| GET    | `/users`                  | Obtener lista de usuarios.             |
| GET    | `/topics`                 | Listar todos los temas.                |
| POST   | `/topics`                 | Crear un nuevo tema.                   |
| GET    | `/courses`                | Listar todos los cursos.               |
| POST   | `/responses`              | Publicar una respuesta en un tema.     |

