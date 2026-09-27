# Demo Backend: Keycloak Spring Boot Adapter

[![Java 8](https://img.shields.io/badge/Java-8-orange.svg?style=flat&logo=openjdk)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.2.7-brightgreen.svg?style=flat&logo=springboot)](https://spring.io/projects/spring-boot)
[![Keycloak](https://img.shields.io/badge/Keycloak-Adapter-blue.svg?style=flat&logo=redhat)](https://www.keycloak.org/)

Repositorio complementario para los videos prácticos de la serie tutorial en YouTube sobre autenticación y autorización con Keycloak y Spring Boot.

> 📌 **Arquitectura Completa y Microservicios:**  
> Este repositorio contiene la implementación backend inicial utilizada en los primeros capítulos demostrativos.  
> Para la arquitectura modular completa con múltiples microservicios (**Products** y **Suppliers**) y cliente **Angular** integrado con interceptores HTTP, consultá el repositorio principal:  
> 🔗 **[KeyCloak-Angular-Spring](https://github.com/vargasjuanj/KeyCloak-Angular-Spring)**

---

## 📺 Serie en YouTube
* 📺 **[Lista de reproducción completa en YouTube](https://www.youtube.com/playlist?list=PLxD7UVJ_L1lSoBUlvVzxP3wqGvuFS5S23)**

---

## ⚙️ Configuración y Ejecución

1. Iniciar Keycloak en `http://localhost:8080` e importar el realm `E-Commerce`.
2. Ejecutar la aplicación Spring Boot:
   ```bash
   ./mvnw clean spring-boot:run
   ```
   El servicio estará disponible en `http://localhost:8081`.
