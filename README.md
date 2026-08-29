<div align="center">

# Kong Yu Min

**Cybersecurity-focused Computing Science Student · University of Glasgow**

<a href="https://github.com/DenverCoder1/readme-typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2EE6A6&center=true&vCenter=true&width=650&lines=Aspiring+SOC+Analyst+%2F+Security+Engineer;Building+detection+%26+response+systems;Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL+%C2%B7+Docker;Open+to+Summer+2027+internships" alt="Typing SVG" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kong--yu--min-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kong-yu-min)
[![Email](https://img.shields.io/badge/Email-yumin05.uk%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:yumin05.uk@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-noMoney-212C42?style=flat-square)](https://tryhackme.com/p/noMoney)

</div>

<br>

### ▎Who I Am

- 🔐 Penultimate-year BSc Computing Science student, aiming for **SOC analyst / security engineering** roles
- 🛠️ Shipped LDR Platform v1.1 (self-built mini SOC) — now building Verafield, an EUDR compliance evidence platform
- 📡 Completed TryHackMe's Pre Security, Cyber Security 101 and SOC Level 1 — now on the **Security Engineer** path
- 🎯 Targeting SOC Analyst / Security Engineer internships at finance & tech, Summer 2027
- 💬 Always happy to chat cybersecurity or software engineering

<br>

### ▎Tech Stack

| Layer | Technologies |
|---|---|
| **Core** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square) ![Alembic](https://img.shields.io/badge/Alembic-2C2D72?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)|
| **Testing & Quality** | ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black) |
| **Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Security Tools** | ![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C0102D?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white) ![Elastic](https://img.shields.io/badge/Elastic-00BFB3?style=flat-square&logo=elastic&logoColor=white) |
| **Secondary** |  ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)  ![structlog](https://img.shields.io/badge/structlog-0D1117?style=flat-square) |

<br>

### ▎Project Case Studies

**LDR Platform — Mini SOC Platform**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C0102D?style=flat-square)

**The Challenge:** Turn raw Flask/Nginx logs into something an analyst can actually act on — not a log viewer, but real detection, investigation, and response with a defensible audit trail.

**The Solution:** An ingest API normalises logs into an ECS-inspired schema; a polling worker evaluates YAML threshold rules mapped to MITRE ATT&CK and writes alerts; a Flask dashboard lets an analyst triage, pivot to an IP's timeline, and block/unblock — every action chained into a tamper-evident sha256 audit log.

```
Agent → Ingest API → Normaliser → Event Store (Postgres)
                                        ↓
                                Detection Worker (YAML rules)
                                        ↓
                                 Alert Writer → Email
                                        ↓
                             Investigation Dashboard
                                        ↓
                           Response Actions → Audit Log
```

[LDR Platform Repo →](https://github.com/minkong05/LDR-platform)

---

**Verafield — EUDR Regulatory Compliance Platform** *(in progress)*
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Alembic](https://img.shields.io/badge/Alembic-2C2D72?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**The Challenge:** Independent oil-palm smallholders need to prove EU Deforestation Regulation compliance — resolving what documents they hold against a versioned state-tenure rulebook, cross-checking field signals for anomalies, and assembling it all into an evidence pack a mill can send to its EU buyer.

**The Solution:** A FastAPI backend across ten routers with schema-level multi-tenant isolation — every child row uses a composite foreign key on `(parent_id, mill_id)`, so one tenant's records can't be linked to another's even if application code forgets to filter. A versioned rules engine (seeded through Alembic migrations) resolves state + land type to exact required documents, a verification engine routes inconsistent field signals to human review, and an evidence-pack generator assembles cleared records into a regulator-mapped output only once every flag on the batch clears.

```
Mill Dashboard (teammate)     Field Collector (teammate)
              ↘                     ↙
             backend/routes  —  10 routers (mine)
                          ↓
                   Rules Engine
     state + land type → required docs (versioned rulebook)
                          ↓
                Verification Engine
      deforestation test + Five-Point Field Check
                          ↓
        inconsistent ──→ needs_review queue (human)
                          ↓ cleared
              Evidence Pack Generator
        Annex II JSON + GeoJSON  →  mill  →  EU buyer
```

*Team project, in progress — pre-MVP, backend feature-complete through roadmap feature 9. This card covers only the FastAPI backend and shared `packages/shared_types` contract, my own work. The React/TypeScript mill dashboard and the offline field-collector app are built by a teammate; both integrate against my API without touching the service or database layers directly.*

[Verafield Repo →](https://github.com/minkong05/Verafield)

---

**Flask-LearnPython — Security-Focused Learning Platform**
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![CSRF](https://img.shields.io/badge/CSRF_protection-212C42?style=flat-square) ![Rate Limiting](https://img.shields.io/badge/Rate_limiting-212C42?style=flat-square) ![Docker Sandbox](https://img.shields.io/badge/Docker_sandbox-2496ED?style=flat-square&logo=docker&logoColor=white)

**The Challenge:** An interactive Python-learning platform needs to let users run their own code — a textbook remote-code-execution risk if done carelessly.

**The Solution:** User code never touches the Flask process. It's forwarded, authenticated via a shared secret, to a separate sandbox service that runs it in a throwaway Docker container with no network access and hard resource limits — backed by login gates, rate limits, and a code-length cap on the Flask side.

```
Browser
   ↓
Flask App   (login required · rate limit · 1000-char cap · timeout)
   ↓  X-SANDBOX-SECRET
Sandbox Service   (separate process, :5001)
   ↓
Docker container   (--network=none --memory=128m --cpus=0.5 --pids-limit=32)
```

[Flask-LearnPython Repo →](https://github.com/minkong05/Flask-Learnpython)

---

**Socket-Transfer-App — Custom TCP File-Transfer Protocol**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Sockets](https://img.shields.io/badge/Raw_sockets-212C42?style=flat-square) ![Protocol Design](https://img.shields.io/badge/Protocol_design-212C42?style=flat-square)

**The Challenge:** Understand how application-layer protocols actually work by building one from raw TCP sockets — standard library only, no framework doing the work underneath.

**The Solution:** A custom client-server protocol with handshake validation and fixed-length framing. An 8-byte big-endian header precedes every file payload, so both sides always know exactly how many bytes to expect.

```
Client → command line   (LIST / GET|file / PUT|file)
              ↓
Server → handshake   (exactly "OK" or "ER")
              ↓
8-byte length header + raw file bytes
              ↓
        File transferred
```

[Socket-Transfer-App Repo →](https://github.com/minkong05/Socket-Transfer-App)

<br>

### ▎Engineering Roadmap

```
2024 ─────────────────────────────────────────────────────────────────── 2027
 │
 ├─ [✓] TryHackMe: Pre Security → Cyber Security 101 → SOC Level 1
 ├─ [✓] LDR Platform v1.0.0 — detection, dashboard, response, audit trail
 ├─ [✓] MITRE ATT&CK mapping + tamper-evident hash-chained audit log
 │
 ├─ [~] TryHackMe: Security Engineer path
 ├─ [~] Verafield — EUDR compliance evidence platform
 ├─ [~] LeetCode — arrays, hashmaps, sliding window
 │
 ├─ [ ] TryHackMe: Pentesting path + Kali Linux
 └─ [ ] Summer 2027 — SOC Analyst / Security Engineer internship
```

<br>

### ▎GitHub Stats
<div align="center">
<img src="https://streak-stats.demolab.com/?user=minkong05&theme=dark&hide_border=true" height="165" />
</div>

<br>

<div align="center">

*Open to cybersecurity internships & placements — Summer 2027*

</div>
