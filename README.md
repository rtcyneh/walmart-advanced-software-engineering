# Walmart Global Tech USA: Advanced Software Engineering Enterprise Simulation

This repository contains production-ready implementations and architectural solutions for the Walmart USA Advanced Software Engineering Job Simulation via Forage. 

Unlike standard boilerplate submissions, this project treats each task through the lens of production scale, algorithmic optimization, performance profiling, and defensive software architectures.

---

## 🚀 Repository Highlights (Why This Project Stands Out)
*   **Generic Profile-Ready Heap (Task 1):** Upgraded the base multi-child heap array allocation using standard Java Generics (`<T extends Comparable<T>>`) and designed a dedicated runtime benchmark tool.
*   **Architecture-as-Code Workflow (Task 2):** Modeled enterprise relational structures directly inside native Markdown utilizing Mermaid.js syntax.
*   **Defensive & Fault-Tolerant ETL Pipeline (Task 4):** Formulated a Python pipeline complete with explicit system tracking (`logging`) and an isolation mechanism (Dead-Letter Queue) preventing catastrophic data pipeline crashes from corrupt inputs.

---

## 🛠️ Global Tech Stack
*   **Languages:** Java 17+, Python 3.10+, Standard ANSI SQL (SQLite dialect)
*   **Design & Architecture:** Mermaid.js, Relational 3NF Schema Optimization
*   **Core Concepts:** Custom Memory Heaps, Performance Profiling, Relational Algebra, Fault Tolerance, Structured Logging

---

## 📂 Structural Deep Dive

### 🧬 1. Custom Data Structures & Profiling (`/task-1-advanced-data-structures`)
*   **Objective:** Implement a parameterized multi-child Max Heap where parent nodes contain 2^x children.
*   **Engineering Edge:** Designed an automated framework tracking exact operational execution differences across variable branch counts (2, 4, 8) utilizing 100,000 algorithmic instances.
*   *Documentation:* Review metrics inside [BENCHMARK_REPORT.md](./task-1-advanced-data-structures/BENCHMARK_REPORT.md).

### 🏗️ 2. Enterprise System Architecture (`/task-2-software-architecture`)
*   **Objective:** Formulate a decoupled object model mapping out Walmart's proprietary supply chain logistical rules.
*   **Engineering Edge:** Utilized strong Design Pattern standards (Data Transfer Objects, Inversion of Control concepts) instead of fragile tight-coupling setups.
*   *Documentation:* View structural layout inside [ARCHITECTURE.md](./task-2-software-architecture/ARCHITECTURE.md).

### 🗄️ 3. Optimized Transaction Schema Design (`/task-3-relational-database-design`)
*   **Objective:** Structure flat retail records into standardized relational entities.
*   **Engineering Edge:** Integrated explicit table integrity conditions (`CHECK` constraints) alongside explicit transaction indexing keys (`CREATE INDEX`) to boost system querying velocities.
*   *Documentation:* Review database breakdown inside [SCHEMA_DESIGN.md](./task-3-relational-database-design/SCHEMA_DESIGN.md).

### 🐍 4. Production Data Munging Pipeline (`/task-4-data-munging`)
*   **Objective:** Construct an enterprise-grade script converting loose transaction documents safely into relational structures.
*   **Engineering Edge:** Crafted a programmatic framework preventing crash occurrences through the execution of quarantine loops routing bad rows to separate data stores.
*   *Documentation:* Read runtime policies inside [PIPELINE_DOCS.md](./task-4-data-munging/PIPELINE_DOCS.md).

---
*Disclaimer: Developed solely for showing personal implementation capabilities based on scenario templates provided by Walmart USA via Forage.*
