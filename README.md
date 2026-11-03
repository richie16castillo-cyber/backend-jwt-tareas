# API REST con Autenticación JWT y CRUD de Tareas

Backend desarrollado en **Node.js** y **Express** con base de datos **MongoDB**. Implementa autenticación basada en tokens JWT (JSON Web Tokens) y un sistema CRUD de tareas protegido con Bearer Token, garantizando el aislamiento de datos por usuario (cada usuario solo puede consultar, editar y eliminar sus propias tareas).

---

## Características
- Registro e inicio de sesión de usuarios con contraseñas encriptadas mediante `bcrypt`.
- Generación y verificación de tokens de autenticación `JWT`.
- Middleware de protección para validar tokens en el header `Authorization: Bearer <token>`.
- CRUD de tareas completamente aislado y restringido por el ID del usuario en sesión.
- Manejo centralizado de errores y códigos de estado HTTP estándar.

---

## Requisitos Previos
- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) o una instancia local de MongoDB
- [Postman](https://www.postman.com/) o [Insomnia](https://insomnia.rest/) para pruebas de endpoints

---

## Instalación

1. Clona este repositorio o descárgalo:
git clone https://github.com/richie16castillo-cyber/backend-jwt-tareas.git
cd backend-jwt-tareas
