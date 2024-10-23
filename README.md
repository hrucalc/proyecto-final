# 📚 Proyecto Final: Sistema de Reconocimiento Facial y Control de Asistencia

Este repositorio es un proyecto final que consiste en un sistema de reconocimiento facial y control de asistencia diseñado para ser low-cost, enfocado en registrar de manera efectiva la entrada y salida de los maestros en una escuela. Su objetivo es proporcionar una solución económica y sistematizada que minimice gastos excesivos en servicios de asistencia. El sistema está compuesto por dos submódulos: el backend, que gestiona la API para el reconocimiento facial y el control de asistencia, y el frontend, que ofrece una interfaz de usuario intuitiva.



## 🌐 Estructura del Proyecto

```
/proyecto-final
├── backend               # Submódulo para el backend del sistema
│   └── README.md         # Detalles sobre el backend
├── frontend              # Submódulo para el frontend del sistema
│   └── README.md         # Detalles sobre el frontend
```

### 🚀 Backend

El backend está construido con **FastAPI** y utiliza **OpenCV** y **MTCNN** para el reconocimiento facial. Proporciona una API REST para gestionar usuarios, registros de asistencia y comparar rostros.

- **Repositorio**: [proyecto-final-backend](https://github.com/hrucalc/proyecto-final-backend)

### 🌈 Frontend

El frontend está diseñado para interactuar con el backend, permitiendo a los usuarios registrar su asistencia y ver la información de los usuarios y registros.

- **Repositorio**: [proyecto-final-frontend](https://github.com/hrucalc/proyecto-final-frontend)

## 📜 Instrucciones para Clonar y Configurar el Proyecto

Para trabajar con este proyecto en tu entorno local, sigue estos pasos:

1. **Clona este repositorio**:
   ```bash
   git clone --recurse-submodules <URL_DEL_REPOSITORIO_PRINCIPAL>
   cd mi-proyecto
   ```

2. **Navega a cada submódulo y sigue las instrucciones de instalación específicas**.

### 🏗️ Configuración del Backend

Para más detalles sobre cómo configurar y ejecutar el backend, consulta el README en el submódulo del backend.

### 🖥️ Configuración del Frontend

Para más detalles sobre cómo configurar y ejecutar el frontend, consulta el README en el submódulo del frontend.

## 📜 Funcionalidades Principales

### Desde el Backend

- **Registro de Usuario**: Permite registrar nuevos usuarios con reconocimiento facial.
- **Actualización de Usuario**: Facilita la actualización de información de usuarios registrados.
- **Comparación Facial**: Verifica la identidad del usuario mediante comparación de imágenes.
- **Registro de Marcajes**: Guarda registros de entradas y salidas de los usuarios.

### Desde el Frontend

- **Registro de Usuario**: Interfaz para que los usuarios registren su asistencia.
- **Actualización de Usuario**: Opción para actualizar información del usuario.
- **Marcaje de Entrada y Salida**: Interfaz para registrar entradas y salidas mediante reconocimiento facial.
- **Interfaz de Usuario Intuitiva**: Navegación sencilla y accesible.

## 🛠️ Tecnologías Utilizadas

- **Backend**:
  - **Python**: Lenguaje de programación principal.
  - **FastAPI**: Framework para la creación de la API REST.
  - **OpenCV**: Biblioteca para la manipulación de imágenes.
  - **MTCNN**: Detector de rostros.
  - **SQLite**: Base de datos.

- **Frontend**:
  - **HTML**: Estructura básica de la aplicación.
  - **CSS**: Estilos para mejorar la apariencia.
  - **JavaScript**: Lógica del frontend, incluyendo la interacción con la API.
  - **Bootstrap**: Framework CSS para diseño responsivo.

## 👥 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas contribuir, sigue estos pasos:

1. Realiza un _fork_ del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y _commits_ (`git commit -am 'Agregué una nueva funcionalidad'`).
4. Sube la rama (`git push origin feature/nueva-funcionalidad`).
5. Crea un nuevo _Pull Request_.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo `LICENSE`.