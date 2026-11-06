<div align="center">

# Sebastián Cardona | Ingeniero de Software
### Ingeniero y Desarrollador Backend

Santa Marta, Colombia · Remoto & Relocalización  
[LinkedIn](https://linkedin.com/in/sebastiansaintt) &nbsp;|&nbsp; [GitHub](https://github.com/sebastiansaintt) &nbsp;|&nbsp; [Email](mailto:scarrdona@gmail.com)

</div>

---

<table>
  <tr>
    <td width="72%" valign="top">
      <h3>Perfil Profesional</h3>
      <p>
        Ingeniero de Software enfocado en el diseño de <b>arquitecturas backend de alto rendimiento</b>, <b>APIs resilientes</b> y <b>sistemas distribuidos seguros de extremo a extremo (E2E)</b>.
      </p>
      <p>
        Mi enfoque técnico prioriza los fundamentos de ingeniería: diseño desacoplado (<i>Clean Architecture, SOLID, MVC</i>), persistencia transaccional estricta (<i>ACID</i>) y desarrollo defensivo bajo estándares <b>OWASP</b>. Cuento con experiencia integrando flujos de datos que abarcan desde el borde (telemetría e IoT con microcontroladores) hasta servicios cloud y aplicaciones web/móviles reactivas.
      </p>
      <p>
        <b>Posición actual:</b> Auxiliar de Investigación con <b>React Native</b> en la Universidad Antonio Nariño.
      </p>
      <p>
        <b>Disponibilidad:</b> Contratación remota internacional y proyectos de alta exigencia técnica.
      </p>
    </td>
    <td width="28%" align="center" valign="middle">
      <img src="IMG_4596.jpeg" alt="Sebastián Cardona" width="180" style="border-radius: 12px; border: 1px solid #334155;" />
    </td>
  </tr>
</table>

---

### Principios de Ingeniería & Arquitectura

- **Rendimiento y Escalabilidad:** Implementación de servicios asíncronos y no bloqueantes con FastAPI y Node.js, optimizados para baja latencia, alto volumen de peticiones y comunicación bidireccional vía WebSockets.
- **Seguridad Defensiva (Zero-Trust):** Autenticación criptográfica con JWT asimétrico (RS256) y simétrico (HS256), rotación controlada de access/refresh tokens, cookies HttpOnly/SameSite, autorización granular basada en roles (RBAC), hashing Argon2id y revocación de sesiones distribuida en Redis.
- **Ciclo de Vida E2E:** Capacidad comprobada para diseñar, modelar, construir y desplegar la solución completa: adquisición de datos en el cliente o sensor, transporte seguro, procesamiento en servidor, almacenamiento estructurado y consumo en interfaces modernas.
- **Calidad y Mantenibilidad:** Código modular, tipado estricto (TypeScript, Pydantic), separación clara de responsabilidades y orquestación reproducible mediante Docker y Docker Compose.
- **AI Integration:** RAGs (semantic search, embeddings), Multi-Models, Workflows, Claude Code.

---

### Capacidades Técnicas

| Dominio | Tecnologías y Herramientas |
| :--- | :--- |
| **Backend & APIs** | Python, FastAPI, Node.js, Express, Next.js, WebSockets, RESTful APIs, Pydantic |
| **Bases de Datos & Caché** | PostgreSQL, Redis, SQLAlchemy, Alembic, Modelado Relacional (ACID), Supabase |
| **Frontend & Mobile** | TypeScript, JavaScript, React, React Native, Vue.js, Tailwind CSS, Vite, PWA |
| **IoT & Streaming de Datos** | MQTT (HiveMQ Cloud), Telemetría en tiempo real, Microcontroladores ESP32 |
| **Seguridad & Estándares** | OWASP Top 10, JWT, Argon2id, RBAC, Rate Limiting, Sanitización de Entradas |
| **DevOps & Entorno** | Docker, Docker Compose, Git, GitHub Actions, AWS, Linux, Render |

---

### Sistemas Desarrollados

#### 1. Car Inspection Platform | VEYRA
*Arquitectura Full Stack, Seguridad Enterprise y Modo Progresivo (2026)*

- **Problema:** Reemplazo integral de auditorías manuales en papel en el sector de transporte de carga y vehículos especiales por una solución digital verificable en tiempo real.
- **Arquitectura:** Monolito modular por capas (Layered + MVC) con backend asíncrono en FastAPI y cliente desacoplado en React y TypeScript configurado como PWA.
- **Implementación de Seguridad:** Esquema de autenticación estricto con JWT, cookies HttpOnly, autorización por roles (RBAC), hashing Argon2id, revocación instantánea de credenciales en Redis y validación de esquemas en servidor.
- **Stack:** FastAPI, React, TypeScript, PostgreSQL, SQLAlchemy, Redis, Docker Compose.
- **Código:** [github.com/sebastiansaintt/car_checking](https://github.com/sebastiansaintt/car_checking)

#### 2. Real-Time Fermentation Pipeline | Pipeline de Telemetría Industrial
*Ingeniería de Datos, Eventos en Tiempo Real y Conectividad IoT (2025 - 2026)*

- **Problema:** Monitoreo y control continuo de variables críticas (CO2, temperatura y humedad) en procesos de fermentación artesanal para mitigación de mermas operativas.
- **Arquitectura:** Pipeline de ingesta distribuido que captura señales desde microcontroladores ESP32, transportadas mediante broker MQTT hacia un backend de procesamiento en FastAPI con persistencia histórica en PostgreSQL.
- **Transmisión y Despliegue:** Difusión en vivo hacia tableros de control mediante WebSockets y background workers concurrentes desplegados en contenedores.
- **Stack:** FastAPI, MQTT, WebSockets, PostgreSQL, Supabase, Docker, ESP32.
- **Código:** [github.com/realprodigium/risk_follower](https://github.com/realprodigium/risk_follower)

#### 3. LawSim Pymes | Plataforma de Simulación Regulatoria
*Arquitectura Empresarial, Microservicios y Razonamiento Ontológico (2025)*

- **Problema:** Automatización y simulación de cumplimiento legal y normativo para pequeñas y medianas empresas mediante evaluación de reglas de negocio complejas.
- **Arquitectura:** Sistema híbrido (Capas + Microservicios + MVC) estructurado para desacoplar las operaciones transaccionales del pipeline de inferencia lógica.
- **Modelado Normativo:** Integración de ontologías de dominio formalizadas en OWL 2 (Protégé) procesadas mediante motor de inferencia HermiT, reglas SWRL y clasificación con procesamiento de lenguaje natural (LEGAL-BETO).
- **Stack:** FastAPI, Vue.js, OWL 2 / Protégé, SWRL, Redis Cache, JWT RS256, SOAP/WSDL.
- **Código:** [github.com/sebastiansaintt/WebDesign](https://github.com/sebastiansaintt/WebDesign)

---

### Formación

- **Pregrado en Ingeniería de Software (2022 — 2026)**  
  *Universidad Cooperativa de Colombia*  
  Especialización académica en sistemas distribuidos, arquitectura de software, bases de datos y seguridad computacional.

- **Certificación en Habilidades Directivas y Comunicación Técnica (2024)**  
  *HabComLearn (HCL)*  
  Gestión ágil de proyectos (Scrum), comunicación técnica asertiva y coordinación de equipos de ingeniería.

---

### Contacto Directo

- **Ubicación:** Santa Marta, Colombia
- **Correo electrónico:** [scarrdona@gmail.com](mailto:scarrdona@gmail.com)
- **LinkedIn:** [linkedin.com/in/sebastiansaintt](https://linkedin.com/in/sebastiansaintt)
- **GitHub:** [github.com/sebastiansaintt](https://github.com/sebastiansaintt)
