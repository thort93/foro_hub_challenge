# 🚀 Foro Hub

<p align = "center">
<img src="https://github.com/thort93/foro_hub_challenge/blob/main/Badge-Spring.png?raw=true" width="200" >
</p>


Foro Hub es una API REST desarrollada con Spring Boot. Permite a los usuarios crear, leer, actualizar y eliminar tópicos de manera segura.
La API sigue las mejores prácticas REST, incluyendo validaciones de datos, manejo de errores, y control de acceso mediante autenticación y autorización JWT.
La información se almacena en una base de datos relacional (MySQL), asegurando persistencia y consistencia.
Ideal para aplicaciones educativas, comunidades online o como base para proyectos de foros modernos..  

---

## 🛠 Tecnologías

- 💻 **Java 17**  
- 🌱 **Spring Boot 3.1.3**  
 🗄 **MySQL 8**
- 📦 **Hibernate 6**  
- 🔒 **Spring Security + JWT**  
- ✏️ **Lombok**  

---

## ✨ Funcionalidades

- 🔑 Autenticación con JWT y encriptación de contraseñas (BCrypt).  
- 📝 Crear, listar, actualizar y eliminar **tópicos**.  
- 📚 Gestión de cursos y asociación con tópicos y autores.  
- 🚦 Control de acceso con anotaciones `@PreAuthorize`.  
---

## 💬 Tópicos
Método	Endpoint	Roles	Descripción
GET	/api/topicos	USER, MODERATOR, ADMIN	Listar tópicos
POST	/api/topicos	MODERATOR, ADMIN	Crear tópico
GET	/api/topicos/{id}	USER, MODERATOR, ADMIN	Obtener tópico por ID
PUT	/api/topicos/{id}	MODERATOR, ADMIN	Actualizar tópico
DELETE	/api/topicos/{id}	ADMIN	Eliminar tópico

## ▶️ Cómo ejecutar

Clonar repo:

git clone https://github.com/thort93/foro_hub_challenge.git


Configurar la DB en application.properties.

Ejecutar proyecto:

mvn spring-boot:run


Testear endpoints en Postman o Insomnia.

## recuerda descomprimir el archivo .RAR
