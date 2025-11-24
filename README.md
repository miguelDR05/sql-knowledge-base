# 🗄️ SQL Knowledge Base & Portfolio

![SQL](https://img.shields.io/badge/SQL-Database%20Engineering-005C84?style=for-the-badge&logo=postgresql)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 🚀 About

Welcome to my personal collection of advanced SQL scripts, optimization techniques, and database administration utilities. 

This repository serves as a **centralized knowledge base** containing reusable patterns and solutions I've developed throughout my career in software development and data engineering. It demonstrates generic implementations compatible with major database engines.

## 🛠️ Technologies

The scripts included here cover various RDBMS dialects:

* **Microsoft SQL Server (T-SQL)**
* **PostgreSQL (PL/pgSQL)**
* **MySQL / MariaDB**
* **Generic ANSI SQL**

## 📂 Repository Structure

The repository is organized by engine and category for easy navigation:

```text
.
├── 📁 sql-server/
│   ├── 📂 administration/   # Backups, user permissions, log maintenance
│   ├── 📂 optimization/     # Index fragmentation, execution plan analysis
│   └── 📂 stored-procs/     # Reusable stored procedures templates
├── 📁 postgresql/
│   ├── 📂 json-handling/    # JSONB queries and manipulation
│   └── 📂 window-functions/ # Advanced analytical queries
├── 📁 mysql/
│   └── 📂 patterns/         # Common patterns adapted for MySQL
└── 📁 universal-patterns/
    ├── recursive-ctes.sql   # Hierarchical data queries
    └── pivot-tables.sql     # Dynamic pivoting examples

💡 Highlights
Some interesting problems solved in this repo:

Dynamic Pivoting: Handling datasets with unknown column numbers at runtime.

Gaps and Islands: Identifying missing sequences in data series.

Recursive Queries: Traversing tree-like structures (e.g., organizational charts or category trees).

Performance Tuning: Queries to identify bottlenecks and deadlocks.

⚠️ Disclaimer
These scripts are intended for educational purposes and reference. While they are based on production scenarios, always review and test code before running it in a production environment.

📫 Contact
If you find a bug or have a suggestion to optimize a query, feel free to open an issue!

Portfolio/Web: https://porfolio-migueldr05.netlify.app/

Email: miguel05.dev@gmail.com
