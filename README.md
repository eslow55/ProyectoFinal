# 🏰 Sistema de Coordinación Estratégica - Cuerpo de Cazadores

API REST desarrollada con Spring Boot para la gestión táctica de los Pilares durante la batalla del Castillo Infinito.

## 📋 Integrante
- **Nombre:** Juan Sebastian Martinez Asprilla
- **Curso:** Examen Final Java Spring Boot

## 🛠️ Tecnologías
- Java 17 / 21
- Spring Boot 3
- MySQL (XAMPP)
- Maven

## 🚀 Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. Importar como **Existing Maven Project** en Eclipse.
3. Crear o cargar la base de datos que esta en resourse en MySQL llamada `castillo_db`.
4. Configurar usuario en `src/main/resources/application.properties`.
5. Ejecutar `CastilloApplication.java`.

## 📡 Endpoints Probados
| Método | URL | Descripción |
|--------|-----|-------------|
| GET | `/api/inteligencia/triangulacion` | Calcula ubicación enemiga |
| POST | `/api/pilares/crear` | Crea un nuevo pilar |
| GET | `/api/pilares/{id}` | Busca un pilar por ID |
