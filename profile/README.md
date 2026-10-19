# ITAM — Database Systems Course Hub

Course infrastructure, containerized laboratory setups, and practical exercises for database systems courses at [Instituto Tecnológico Autónomo de México (ITAM)](https://www.itam.mx/).

[![Institution](https://img.shields.io/badge/ITAM-Computer_Science-004B49?style=flat-square)](https://www.itam.mx/)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Distributed-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

---

### 📚 Curriculum & Courses

| Course | Code | Environment & Core Repositories | Key Topics Covered |
|---|---|---|---|
| **Bases de Datos**<br>*(Relational Databases)* | `COM-12101` | • [relational-dbs-labs-setup](https://github.com/mavasbel-itam/relational-dbs-labs-setup)<br>• [api-amazon](https://github.com/mavasbel-itam/api-amazon)<br>• [api-youtube](https://github.com/mavasbel-itam/api-youtube) | Relational algebra, SQL, normal forms, transaction ACID properties, indexing, triggers, and external REST API integrations. |
| **Bases de Datos No Relacionales**<br>*(Non-Relational Databases)* | `COM-22102` | • [non-relational-dbs-labs-setup](https://github.com/mavasbel-itam/non-relational-dbs-labs-setup) | Polyglot persistence, document databases (MongoDB), distributed key-value stores, wide-column architectures, and event streaming. |

---

### 🚀 Lab Quick Start Guide

All course laboratories use containerized stacks to ensure uniform evaluation across Linux, macOS, and Windows:

```bash
# 1. Clone the appropriate lab repository
git clone https://github.com/mavasbel-itam/relational-dbs-labs-setup.git
cd relational-dbs-labs-setup

# 2. Launch the isolated multi-container database stack
docker compose up -d

# 3. Verify container health
docker compose ps
```

> [!NOTE]
> Detailed per-lab exercise instructions, grading criteria, and dataset fixtures are hosted within each specific laboratory repository.

---

### 🔒 Access & Maintenance Notice

* **Instructor Infrastructure:** Graders, solution branches, and reference stream consumers are maintained in private repositories.
* **Affiliation Disclaimer:** This organization is maintained by course instructor [Marco Vásquez Beltrán](https://github.com/mavasbel) as a courseware hub and is not an official administrative account of ITAM.
