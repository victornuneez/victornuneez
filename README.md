<div align="center">

<!-- Typing SVG Animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Hey+there!+I'm+Victor+Nunez+👋;Backend+Developer+Jr.;Python+%7C+Node.js+%7C+JavaScript+%7C+SQL;Building+cool+things+from+Paraguay+🇵🇾)](https://git.io/typing-svg)

---

<!-- Matrix Rain Animation -->
<img src="https://raw.githubusercontent.com/victornuneez/victornuneez/main/matrix.svg" width="700" alt="Matrix Rain"/>

</div>

---

## 👨‍💻 Sobre mí

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&width=700&lines=📍+Asunción%2C+Paraguay+🇵🇾;🐧+Estudiante+CodePRO+%40+Penguin+Academy;🏆+Team+Lead+%40+HackathonPenguin;🔐+Apasionado+por+Seguridad+y+Microservicios;🚀+%22Si+falla+lo+depuro.+Si+funciona+lo+escalo.%22)](https://git.io/typing-svg)

</div>

---

## 🛠️ Stack Tecnológico

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

</div>

---

## ⭐ Proyectos Destacados

> Los proyectos que mejor representan mi nivel técnico actual como Backend Developer.

---

### 🛡️ Advanced Auth & Security Shield
> **Sistema de Autenticación Híbrido de grado profesional — Node.js + Express**

Implementación de **Defensa en Profundidad** contra el OWASP Top 10. Combina JWT stateless con sesiones stateful y múltiples capas de protección activa.

| Capa de Seguridad | Implementación |
|---|---|
| 🔐 Auth Híbrida | JWT (Access + Refresh Tokens) + `express-session` |
| 🛡️ Anti-CSRF | Validación de tokens en cada petición con cookie |
| 🧹 Anti-XSS | Middleware custom que sanitiza username, email y password |
| 🔒 Rate Limiting | Bloqueo por ventana de tiempo en el endpoint de login |
| 👑 RBAC | Rutas críticas restringidas exclusivamente al rol `admin` |
| ⛑️ Helmet.js | Configuración automática de cabeceras HTTP seguras |

**Stack:** `Node.js` `Express` `JWT` `Bcrypt` `Helmet.js` `db-local`
🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle--Challenge08--Authentication)

---

### ⚙️ Ecosistema de Microservicios — Task Manager Pro
> **Arquitectura distribuida con Circuit Breaker — Python + Flask**

Tres microservicios coordinados con JWT entre servicios, bases de datos independientes y tolerancia a fallos propia.

```
┌─────────────────┐     ┌─────────────────┐     ┌──────────────────────┐
│  Auth Service   │◄────│  Task Service   │◄────│ Notification Service │
│  (Puerto 5000)  │     │  (Puerto 5001)  │     │    (Puerto 5002)      │
│  JWT + Bcrypt   │     │  CRUD Tareas    │     │  Circuit Breaker 🔌   │
└─────────────────┘     └─────────────────┘     └──────────────────────┘
```

| Estado Circuit Breaker | Comportamiento |
|---|---|
| 🟢 CLOSED | Todo funciona. Las peticiones fluyen normalmente |
| 🔴 OPEN | Fallo detectado. Bloqueo automático para recuperación |
| 🟡 HALF-OPEN | Petición de prueba. Si pasa, vuelve a CLOSED |

**Stack:** `Python` `Flask` `JWT` `SQLite` `python-dotenv` `werkzeug`
🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle---Challenge06---Microservicios)

---

### 🏙️ La Voz Paraguay — Hackathon Batch 5.0
> **Plataforma ciudadana de reportes comunitarios — Python + Flask**

Proyecto real con impacto social desarrollado en el **Hackathon de Penguin Academy**. Sistema completo con autenticación, panel de administración, API REST y diseño responsive.

| Módulo | Descripción |
|---|---|
| 👥 Roles diferenciados | Ciudadanos y Administradores con lógica separada |
| 📋 Gestión de reportes | CRUD completo de denuncias comunitarias |
| 📱 Interfaz responsive | Bootstrap 5.3 + Jinja2, funciona en móvil y escritorio |
| 🔗 API REST | Endpoint `/api/v1/problemas` para integraciones futuras |
| 🛡️ Seguridad | Bcrypt + Flask-Login + protección SQL Injection |
| 💬 Contacto directo | Integración con WhatsApp para comunicación ciudadana |

**Stack:** `Python` `Flask` `SQLAlchemy` `SQLite` `Bootstrap 5.3` `Flask-Migrate`
🔗 [Ver repositorio](https://github.com/victornuneez/Penguin--Hackaton--La-Voz-Paraguay)

---

### 🗳️ Ranking de Temas — Sistema de Votación (MVC)
> **Aplicación web con CRUD completo y arquitectura MVC — Node.js + PostgreSQL**

Arquitectura limpia con responsabilidades bien definidas y base de datos relacional real en producción.

| Componente MVC | Responsabilidad |
|---|---|
| `models/` | Consultas SQL con `pg pool` hacia PostgreSQL |
| `controllers/` | Lógica de negocio y decisión de vista |
| `views/` | Plantillas EJS con HTML dinámico |
| `routes/` | Endpoints conectados a sus controladores |
| `config/` | Pool de conexiones centralizado |

Ranking dinámico con 🥇🥈🥉, sistema de votación incremental y CRUD con validación de URLs.

**Stack:** `Node.js` `Express` `PostgreSQL` `EJS` `CSS3`
🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle--Challenge07--CRUDJS)

---

## 🔧 Otros Proyectos

> Sistemas distribuidos, algoritmos y programación de bajo nivel.

<details>
<summary><b>📊 Sistema de Logging Distribuido</b> — Python · Flask · SQLite</summary>
<br>

Centralización de logs de múltiples microservicios en tiempo real. Autenticación por token, procesamiento en batch, filtros avanzados por fecha y 3 simuladores independientes (Auth, Email, Payment).

🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle---Challenge05---Logging)
<br>
</details>

<details>
<summary><b>📚 ETL — Catálogo de Libros</b> — Scraping · Google Books API · SQL</summary>
<br>

Pipeline completo que extrae 1,000 libros, los enriquece con la API de Google Books y los almacena en un esquema SQL normalizado con 4 tablas y relaciones Muchos-a-Muchos.

🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle---Challenge04---Web-scraping---BasedeDatos)
<br>
</details>

<details>
<summary><b>💬 Chat Multiusuario en Tiempo Real</b> — Python · Sockets · Threading</summary>
<br>

Sistema cliente-servidor con TCP/IP, hilos independientes por cliente, `threading.Lock` para evitar condiciones de carrera y manejo robusto de desconexiones abruptas.

🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle---Challenge03---Sockets)
<br>
</details>

<details>
<summary><b>🏙️ Navegación Urbana Modular</b> — Python · POO · Algoritmo A*</summary>
<br>

Arquitectura orientada a objetos con 4 módulos desacoplados. A* con costos de terreno dinámicos y recálculo de rutas en tiempo real ante nuevos obstáculos.

🔗 [Ver repositorio](https://github.com/victornuneez/The-huddle---Challenge02---POO)
<br>
</details>

<details>
<summary><b>🗺️ City Pathfinding</b> — Python · A* · Heurística Manhattan</summary>
<br>

Ciudades procedurales con 20% de densidad de edificios y búsqueda de rutas óptimas usando A* con `heapq` (cola de prioridad binaria).

🔗 [Ver repositorio](https://github.com/victornuneez/The-Huddle---Challenge01---Calcudoraderutas)
<br>
</details>

<details>
<summary><b>🌀 Laberinto Maestro</b> — C++ · BFS</summary>
<br>

Generador y resolvedor de laberintos en C++. BFS garantiza el camino más corto con cronómetro de alta resolución para medir rendimiento en milisegundos.

🔗 [Ver repositorio](https://github.com/victornuneez/The-Dive---Challenge02---Laberinto---C-)
<br>
</details>

<details>
<summary><b>🐭🐱 Gato y Ratón</b> — Python · Minimax IA</summary>
<br>

IA adversarial con Minimax que anticipa 4 movimientos adelante. Evaluación con puntajes (+100 captura / -100 escape) para decidir la ruta óptima del gato.

🔗 [Ver repositorio](https://github.com/victornuneez/The-Dive---Challenge01---Minimax)
<br>
</details>

---

---

## 🤝 Contacto

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victornuneez)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/victornuneez)

![Profile Views](https://komarev.com/ghpvc/?username=victornuneez&color=00D9FF&style=for-the-badge&label=VISITAS+AL+PERFIL)

</div>

---

<div align="center">
  <i>⚡ "El mejor código es el que resuelve el problema. El código brillante es el que además lo hace con elegancia." ⚡</i>
</div>
