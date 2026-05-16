<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/609/609803.png" />

# 🏢 Apartment Rental System

### Plataforma de administración y gestión de apartamentos 🚀

<p align="center">
  <b>Apartment Rental System</b> es una aplicación web diseñada para administrar apartamentos, inquilinos y bases de datos distribuidas, desarrollada como entorno de pruebas para sistemas de rendimiento y escalabilidad.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apartment-RentalSystem-4CAF50?style=for-the-badge">
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/ElasticSearch-Analytics-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-api-y-rutas">API</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Apartment Rental System** es una plataforma web desarrollada para administrar información de apartamentos e inquilinos utilizando múltiples motores de base de datos y herramientas de análisis distribuidas.

El proyecto fue construido como un entorno de pruebas para:

- 🏢 Gestión de apartamentos
- 👥 Administración de inquilinos
- 🗄️ Integración de múltiples bases de datos
- ⚡ Pruebas de rendimiento
- 📊 Sistemas distribuidos
- 🔍 Indexación y análisis
- 🌐 Arquitectura escalable
- 🚀 Simulación de carga

Además, el sistema fue utilizado para probar herramientas del laboratorio **Berkeley NetSys Lab** y evaluar comportamiento bajo estrés y balanceo de carga.

---

# ✨ Características

## 🏢 Gestión de apartamentos

- 📋 Administración de unidades
- 👥 Gestión de inquilinos
- 🧾 Registro de información
- 📊 Control administrativo
- 🏠 Seguimiento de propiedades

---

## 🗄️ Bases de datos múltiples

- 🐘 Integración con PostgreSQL
- 🐬 Integración con MySQL
- 🔄 Lectura y escritura simultánea
- 📂 Persistencia distribuida
- ⚡ Manejo de múltiples endpoints

---

## 🔍 ElasticSearch

- 📈 Conteo de índices
- ⚡ Consultas rápidas
- 📊 Indexación de datos
- 🔎 Búsquedas optimizadas

---

## 🚀 Testing y rendimiento

- 📊 Pruebas de carga
- ⚡ Simulación de tráfico
- 🧪 Benchmarking
- 📈 Monitoreo de rendimiento
- 🔥 Stress testing con Apache JMeter

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript
- Interfaces web básicas

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs" />
</p>

- Node.js
- Express.js
- Quilt
- APIs REST

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgresql" />
</p>

- PostgreSQL
- MySQL
- ElasticSearch
- Persistencia distribuida

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker" />
</p>

- Git
- GitHub
- Apache JMeter
- Docker
- Quilt

---

# 📂 Estructura del proyecto

```bash
PlataformaRentaApartamentos/
│
├── quilt-spec/              # Configuración Quilt
├── server/                  # Backend principal
├── routes/                  # Endpoints API
├── database/                # Configuración DB
├── elastic/                 # ElasticSearch
├── tests/                   # Load testing
│
├── main.js                  # Archivo principal Quilt
├── package.json
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Node.js
- npm
- Quilt
- Docker
- PostgreSQL
- MySQL
- ElasticSearch

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaRentaApartamentos.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd PlataformaRentaApartamentos
```

---

## 3️⃣ Instalar dependencias

```bash
cd quilt-spec
npm install
```

---

## 4️⃣ Ejecutar Quilt

Abrir otra terminal y ejecutar:

```bash
quilt daemon
```

---

## 5️⃣ Ejecutar especificación

```bash
quilt run ./main.js
```

---

## 6️⃣ Obtener IP del servidor

```bash
quilt ps
```

Buscar la IP del contenedor web.

---

# 🌐 API y rutas

## 📡 Endpoints disponibles

### 🐘 PostgreSQL API

```bash
ip_address:3000/app/psql/users
```

- GET
- POST

---

### 🐬 MySQL API

```bash
ip_address:3000/app/mysql/users
```

- GET
- POST

---

### 👋 Ruta principal

```bash
ip_address:3000/app/users
```

- GET

---

### 🔍 ElasticSearch

```bash
ip_address:3000/app/elastic/count
```

- GET

---

# 📊 Pruebas de carga

## ⚡ Apache JMeter

El sistema fue diseñado para realizar pruebas de rendimiento utilizando:

- 🔥 Stress testing
- 📈 Simulación de tráfico
- ⚡ Benchmarking
- 📊 Análisis de rendimiento
- 🌐 Pruebas distribuidas

Herramienta recomendada:

```bash
Apache JMeter
```

---

# 📊 Funcionalidades principales

## 👥 Gestión de inquilinos

- Registro de usuarios
- Administración de datos
- Persistencia distribuida
- APIs REST

---

## 🏢 Gestión de propiedades

- Control administrativo
- Gestión de apartamentos
- Monitoreo de registros
- Manejo de información

---

## 🚀 Arquitectura distribuida

- PostgreSQL
- MySQL
- ElasticSearch
- Quilt orchestration

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y pruebas

- Sistemas distribuidos
- Arquitectura escalable
- Integración de bases de datos
- APIs REST
- Benchmarking
- Load testing
- DevOps básico

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Dashboard moderno
- ☁️ Infraestructura cloud
- 🔐 Autenticación JWT
- 📊 Panel analítico
- 🌐 Microservicios
- 🤖 Monitoreo inteligente
- 🔔 Alertas en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por sistemas distribuidos, plataformas empresariales y arquitectura escalable 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source utilizado para pruebas académicas y experimentación de rendimiento.

---

<div align="center">

### 🏢 Apartment Rental System — administración moderna de propiedades e inquilinos 🚀

</div>
