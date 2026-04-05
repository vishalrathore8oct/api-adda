# 🚀 API Adda

> Reusable Auth System + Free API Hub + Developer Platform

---

## 📌 Overview

API Adda is a production-ready backend platform designed to provide:

* 🔐 Reusable Authentication & Authorization system
* 🌐 Public APIs for learning and development
* 📚 Developer-friendly API documentation
* ⚙️ Scalable microservices architecture

---

## 🏗️ Architecture

This project follows a **monorepo structure** using PNPM workspaces:

```
api-adda/
├── apps/
│   ├── auth-service/
│   └── (future services...)
├── packages/
│   ├── auth-lib/
│   └── (shared utilities...)
```

---

## ⚙️ Tech Stack

* **Backend:** Node.js, Express
* **Language:** TypeScript
* **Database:** MongoDB (via Prisma)
* **Monorepo:** PNPM Workspaces
* **Linting:** ESLint
* **Formatting:** Prettier
* **Git Hooks:** Husky + lint-staged

---

## 🔐 Features (Planned)

* [ ] User Signup & Login
* [ ] JWT Authentication
* [ ] Refresh Token System
* [ ] Role-Based Access Control (RBAC)
* [ ] API Gateway
* [ ] Public API Hub
* [ ] Documentation Platform

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vishalrathore8oct/api-adda.git
cd api-adda
```

### 2. Install dependencies

```bash
pnpm install
```

### 3. Run Auth Service

```bash
cd apps/auth-service
pnpm dev
```

---

## 📁 Project Philosophy

> Build once, reuse everywhere.

The goal of API Adda is to create a **plug-and-play backend system** that can be reused across multiple projects without rewriting core functionalities like authentication.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit PRs.

---

## 📜 License

MIT License

---
