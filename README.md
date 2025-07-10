
# 🚛 dbtyre – Helm Charts for Databases

**Think of this as a tyre truck loaded with powerful database tyres – each wheel spins with a different database.**

Welcome to **dbtyre**, a curated collection of production-ready **Helm charts** for popular databases. Just like a tyre truck carries specialized wheels for different terrains, **dbtyre carries Helm charts** for diverse databases like PostgreSQL, MongoDB, MySQL, MSSQL, and more.

---

## 🧩 Concept

Imagine a **lorry with multiple tyres**, and at the **center of each tyre is a logo** – representing a different database.

Each "tyre" is:
- A modular, tested **Helm chart**.
- Plug-and-play for **Kubernetes deployments**.
- Designed to **roll smoothly** into your CI/CD workflows.

---

## 🧱 Included Database Helm Charts

| Database     | Chart Location               | Status   |
|--------------|------------------------------|----------|
| ![Postgres](https://img.shields.io/badge/-PostgreSQL-blue?logo=postgresql&logoColor=white) | [`charts/postgresql`](charts/postgresql) | ✅ Ready |
| ![MongoDB](https://img.shields.io/badge/-MongoDB-green?logo=mongodb&logoColor=white)     | [`charts/mongodb`](charts/mongodb)       | ✅ Ready |
| ![MySQL](https://img.shields.io/badge/-MySQL-lightgrey?logo=mysql&logoColor=blue)        | [`charts/mysql`](charts/mysql)           | 🚧 WIP   |
| ![MSSQL](https://img.shields.io/badge/-MSSQL-8B0000?logo=microsoftsqlserver&logoColor=white) | [`charts/mssql`](charts/mssql)       | ✅ Ready |
| ![Redis](https://img.shields.io/badge/-Redis-red?logo=redis&logoColor=white)             | [`charts/redis`](charts/redis)           | ✅ Ready |

---

## 🚀 Getting Started

### 1. Add dbtyre to your Helm repos

```bash
helm repo add dbtyre https://virsuryaircas.github.io/dbtyre/charts
helm repo update
