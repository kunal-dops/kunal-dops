# Kunal Narwat

Full Stack Developer building production-ready web apps with the MERN stack, Python, and AI integration.

📫 kunalnarwat001@gmail.com &nbsp;·&nbsp; 📍 India &nbsp;·&nbsp; 💼 Open to opportunities

---

### About

I build full-stack applications that work in production — not just demos. My focus is clean API design, secure backends, and AI features that gracefully fall back when an API key isn't available.

I work across both JavaScript (MERN) and Python (FastAPI) stacks, and I enjoy integrating LLMs into real products — whether that's Claude AI for IT troubleshooting or RAG pipelines for document Q&A.

---

### Stack

**Frontend**
React · JavaScript · HTML · CSS · Vanilla JS

**Backend (JS)**
Node.js · Express 5 · JWT · REST APIs

**Backend (Python)**
FastAPI · SQLAlchemy · Alembic · Uvicorn

**Database & Search**
MongoDB Atlas · Mongoose · SQLite · FAISS · BM25

**AI & LLM**
Claude AI (Anthropic SDK) · OpenAI · Ollama · RAG Pipelines · Hybrid Retrieval

**Security**
HttpOnly Cookies · CSRF · RBAC · bcrypt · Rate Limiting · Security Headers

**Tools & DevOps**
Docker · Git · GitHub · Postman · VS Code

---

### Projects

---

#### [AssetSphere Pro](https://github.com/kunal-dops/Asset-management-app)

Full-stack IT Asset Management System for organisations to track hardware, manage assignments, and resolve service requests — with a built-in AI troubleshooter.

**What's inside:**
- Full CRUD REST API with Express 5 + MongoDB Atlas
- JWT authentication with role-based access control (Admin / Technician / User)
- Maintenance request system with a full **audit trail** — every change logs who, what, and when
- AI Troubleshooter powered by **Claude Opus 4.8** (`@anthropic-ai/sdk`) with adaptive thinking
- Graceful fallback to a local keyword-based knowledge base when no API key is set
- Auto-deploys to **Vercel** (frontend) + **Render** (backend) on every push

`React` `Node.js` `Express` `MongoDB` `Claude AI` `JWT` `Vercel` `Render`

---

#### [HR Copilot](https://github.com/kunal-dops/HR-Copilot)

Secure HR Policy Knowledge Portal — admins upload policy documents and employees ask questions answered strictly from the indexed corpus, with source citations.

**What's inside:**
- **RAG pipeline** — FAISS dense retrieval (`all-MiniLM-L6-v2`) + BM25 sparse retrieval fused with RRF
- Document ingestion for PDF, DOCX, and TXT via `pdfplumber` + `python-docx`
- **FastAPI** backend with SQLAlchemy 2.x + Alembic migrations (SQLite default, Postgres-ready)
- Auth: JWT tokens in **HttpOnly cookies**, double-submit CSRF, account lockout after 5 failed attempts
- Rate limiting on login (10/min), password reset (5/min), chat (30/min) via `slowapi`
- Strict CSP, `X-Frame-Options`, HSTS, MIME sniffing protection, sha256 dedup on uploads
- LLM providers: **mock** (default) · **OpenAI** · **Ollama** — switchable via env var
- Vanilla HTML/CSS/JS frontend with no `innerHTML` write paths; Docker Compose included
- Full test suite: login/CSRF/lockout, RBAC enforcement, upload/delete, chat, password reset

`Python` `FastAPI` `SQLAlchemy` `FAISS` `RAG` `OpenAI` `Docker` `SQLite`

---

#### [Weather App](https://github.com/kunal-dops/weather-web-app)

Real-time weather application displaying live temperature and conditions using a weather API.

`JavaScript` `CSS` `Weather API`

---

### GitHub Stats

![Kunal's GitHub Stats](https://github-readme-stats.vercel.app/api?username=kunal-dops&show_icons=true&theme=default&hide_border=true&count_private=true&hide_title=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kunal-dops&layout=compact&theme=default&hide_border=true)

---

### Currently Learning

- System design for scalable APIs
- Docker and containerised deployments
- WebSockets for real-time features
- MongoDB aggregation pipelines

---

*Building things that work in production, not just in demos.*