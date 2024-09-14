# 🚀 **FEVRIPS API Local Docker Setup** 🚀

¡Bienvenido al repositorio para la configuración de Docker de la API local de FEVRIPS! Este proyecto proporciona una configuración completa para ejecutar la base de datos y la API utilizando Docker.

---

## 🛠 **Configuración del Entorno**

Este repositorio incluye una plantilla de Docker Compose para desplegar los siguientes servicios:

- **Base de Datos SQL Server**
- **API Local FEVRIPS**

### 🎯 **Versión del Proyecto**

- **Versión de Docker Compose:** 3.8
- **Versión de API:** 4.1.1

---

## 🔩 **Instrucciones de Configuración**

1. **Login en Azure Container Registry**

   ```bash
   docker login -u puller -p v1GLVFn6pWoNrQWgEzmx7MYsf1r7TKJQo+kwadvffq+ACRA3mLxs fevripsacr.azurecr.io


---

## 🔌 **Iniciar los Servicios**

1. **Para iniciar los servicios, usa el sgte comando**

   ```bash
   docker-compose -f apilocal-dockercompose.yml up -d
