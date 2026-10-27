# 🎓 SoyPilo - Plataforma de Gestión Académica y Estudiantil

**SoyPilo** (evolución del proyecto *NotePro*) es una plataforma web estudiantil desarrollada para instituciones educativas de primaria y secundaria. Su propósito principal es optimizar, ordenar y agilizar los procesos académicos y administrativos, facilitando la comunicación entre la institución, los docentes, los estudiantes y los padres de familia.

El sistema está diseñado para ofrecer una experiencia digital segura, accesible y adaptada a dispositivos móviles, centralizando funciones clave como el control de asistencia, la asignación y entrega de tareas, el registro de notas, la generación de boletines y la gestión de usuarios bajo cuatro roles específicos.

## 👥 Roles del Sistema

La plataforma organiza el acceso y las responsabilidades en cuatro perfiles principales:

1. **Estudiante:** Permite consultar cursos, revisar calificaciones en tiempo real, ver promedios, subir tareas y descargar materiales de estudio.

2. **Padre / Acudiente:** Brinda la capacidad de realizar un seguimiento cercano al rendimiento académico, historial de asistencia y boletines de sus hijos.

3. **Docente:** Facilita la toma de asistencia diaria con fecha y hora automática, la carga y calificación de tareas, la publicación de materiales de apoyo y la generación de reportes.

4. **Directivo / Administrador:** Otorga el control total del sistema para gestionar usuarios, crear cursos, asignar materias a profesores, matricular estudiantes y auditar la plataforma.

## 💻 Lenguajes y Tecnologías del Proyecto

Para el desarrollo de **SoyPilo**, el equipo ha seleccionado una arquitectura desacoplada basada en un cliente web interactivo y un servidor tradicional robusto:

### 1. Frontend (Interfaz de Usuario)

* **JavaScript (ES6+):** Lenguaje principal para la lógica de la interfaz y la interactividad del usuario.

* **ReactJS (con Vite):** Librería basada en componentes reutilizables que permite construir dashboards dinámicos y responsivos que se adaptan automáticamente a cualquier pantalla (celulares, tablets y computadores).

* **HTML5 y CSS3 / Tailwind CSS:** Estructura y diseño visual limpio, intuitivo y uniforme en todas las secciones de la plataforma.

### 2. Backend (Servidor y Lógica de Negocio)

* **PHP (Versión 8.x):** Lenguaje de programación del lado del servidor encargado de procesar las solicitudes de la interfaz, gestionar las reglas de negocio y conectar con la base de datos de forma segura mediante arquitectura API REST.

* **Composer:** Gestor de dependencias de PHP para integrar librerías esenciales como `dompdf` (generación de boletines en PDF) y `PhpSpreadsheet` (exportación de reportes a Excel).

### 3. Base de Datos

* **MySQL / MariaDB (SGBD):** Sistema gestor de bases de datos relacionales estructurado para interconectar de forma precisa los cursos, estudiantes, materias, notas y asistencias, garantizando la integridad de la información y la trazabilidad mediante *triggers* de auditoría.

### 4. Control de Versiones y Despliegue

* **Git y GitHub:** Herramientas de control de versiones colaborativo para que el equipo de desarrollo pueda trabajar simultáneamente en diferentes ramas sin afectar el código principal.

* **XAMPP / Laragon:** Entornos de desarrollo local para la ejecución del servidor PHP y la base de datos MySQL.

## 👨‍💻 Autores y Créditos

Proyecto formativo del **SENA - Servicio Nacional de Aprendizaje** (CIES - Ocaña, Norte de Santander).

* **Ficha:** 3233929 (Levantamiento de Requisitos)

* **Equipo de Desarrollo:**

  * Juan Jose Boada Salazar

  * Miguel Armando Quintero

  * Darin Steven Quintero

* **Instructor:** Azucena Atuesta