# 👋 Hi, I'm Karanjot Singh

### Java Backend Developer | Spring Boot | System Design

I build backend applications with **Java and Spring Boot**, with a strong focus on **clean architecture, secure APIs, database design, and object-oriented software design**.

Currently, I'm deepening my knowledge of **System Design, SOLID principles, Design Patterns, Microservices, and scalable backend architecture**.

<p align="left">
  <a href="https://www.linkedin.com/in/karanjot-singh-172bb3286">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/karanx/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://github.com/karanjot140506">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧑‍💻 About Me

* ☕ Java Backend Developer focused on building **clean and maintainable backend systems**
* 🌱 Currently exploring **Spring Boot, Microservices & System Design**
* 🏗️ Interested in **OOP, SOLID principles, Design Patterns & Clean Architecture**
* 🔐 Building secure REST APIs using **Spring Security & JWT**
* 🗄️ Working with **MySQL, PostgreSQL & MongoDB**
* 🐳 Learning modern development workflows with **Docker & CI/CD**
* 🧠 Consistently solving **DSA problems** to strengthen problem-solving skills
* 🔍 Interested in understanding **how scalable backend systems are designed**

---

# 🛠️ Tech Stack

### ☕ Backend Development

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20MVC-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square" />
</p>

### 🗄️ Databases

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</p>

### 🧠 Software Engineering

`OOP` · `SOLID Principles` · `Design Patterns` · `Clean Architecture` · `REST API Design` · `Database Design` · `System Design`

### 🧰 Tools & DevOps

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-222222?style=flat-square&logo=githubactions&logoColor=white" />
</p>

---

# 🏗️ System Design & Engineering

I'm interested in designing software that is **maintainable, modular, secure, and scalable**.

### Object-Oriented Design

* Abstraction
* Encapsulation
* Inheritance
* Polymorphism
* Composition over inheritance
* Interfaces & loose coupling

### SOLID Principles

* **S** — Single Responsibility Principle
* **O** — Open/Closed Principle
* **L** — Liskov Substitution Principle
* **I** — Interface Segregation Principle
* **D** — Dependency Inversion Principle

### Design Patterns

Currently learning and applying patterns such as:

`Factory` · `Builder` · `Strategy` · `Observer` · `Adapter` · `Singleton` · `Repository` · `MVC`

### System Design Fundamentals

* RESTful API design
* Layered architecture
* Separation of concerns
* Authentication & authorization
* Database design
* SQL vs NoSQL
* Scalability fundamentals
* Caching concepts
* Load balancing concepts
* Microservices fundamentals
* Distributed systems fundamentals

---

# 🚀 Featured Projects

## ☁️ CloudVault — Enterprise Cloud Storage

> A secure cloud-storage application designed around file management, authentication, metadata management, and object storage.

### 🔥 What I Built

* 🔐 JWT-based authentication with Spring Security
* 🛡️ Password hashing and role-based authorization
* 📤 File upload and download
* 🗑️ Recycle-bin and file restoration workflow
* 📦 File metadata management
* 🗄️ MongoDB for application data and metadata
* ☁️ MinIO for S3-compatible object storage
* 🐳 Docker & Docker Compose
* 🧱 Layered backend architecture
* 🔄 RESTful APIs

### 🏛️ Architecture

```text
                    ┌─────────────────┐
                    │     Client      │
                    └────────┬────────┘
                             │
                             │ REST API
                             ▼
                 ┌───────────────────────┐
                 │     Spring Boot       │
                 │                       │
                 │  Spring Security      │
                 │  JWT Authentication   │
                 │                       │
                 │  Controller Layer     │
                 │          ↓            │
                 │  Service Layer        │
                 │          ↓            │
                 │  Repository Layer     │
                 └──────────┬───────┬────┘
                            │       │
                       Metadata    Files
                            │       │
                            ▼       ▼
                       ┌───────┐ ┌────────┐
                       │MongoDB│ │ MinIO  │
                       └───────┘ └────────┘
```

### 🧰 Built With

`Java` · `Spring Boot` · `Spring Security` · `JWT` · `MongoDB` · `MinIO` · `Docker` · `REST APIs`

🔗 **[View CloudVault →](https://github.com/karanjot140506/Cloud-Vault-Enterprise-Storage-Application)**

---

## 🥑 Smart Pantry

> A pantry and inventory management application focused on inventory tracking, expiry management, shopping workflows, and analytics.

### 🔥 What I Built

* 🔐 JWT authentication & authorization
* 🔒 BCrypt password hashing
* 📦 Pantry and inventory management
* ⏰ Expiry tracking and alerts
* 📉 Low-stock detection
* 🛒 Shopping-list workflow
* 🍳 Recipe matching based on available ingredients
* 📊 Expense and inventory analytics
* 🔍 Search, filtering, sorting & pagination
* 📖 Swagger / OpenAPI documentation
* 🐳 Dockerized backend
* ⚠️ Global exception handling
* ✅ Bean validation

### 🏛️ Backend Architecture

```text
             HTTP Request
                   │
                   ▼
          ┌────────────────┐
          │   Controller   │
          └───────┬────────┘
                  │
             Validation
                  │
                  ▼
          ┌────────────────┐
          │    Service     │
          ├────────────────┤
          │ Business Logic │
          │ Expiry Logic   │
          │ Stock Logic    │
          │ Recipe Logic   │
          └───────┬────────┘
                  │
                  ▼
          ┌────────────────┐
          │   Repository   │
          └───────┬────────┘
                  │
                  ▼
             ┌─────────┐
             │ MongoDB │
             └─────────┘
```

### 🧰 Built With

`Java` · `Spring Boot` · `Spring Security` · `JWT` · `MongoDB` · `Docker` · `Swagger/OpenAPI`

🔗 **[View Smart Pantry →](https://github.com/karanjot140506/Smart-Pantry)**

---

# 🧠 Problem Solving

I regularly practice Data Structures & Algorithms to improve my **problem-solving, algorithmic thinking, and ability to reason about efficiency**.

### LeetCode

**700+ problems solved in Java**

Areas I practice include:

`Arrays` · `Strings` · `Hashing` · `Trees` · `Graphs` · `Dynamic Programming` · `Backtracking` · `Greedy Algorithms`

🔗 **[View my LeetCode profile →](https://leetcode.com/u/karanx/)**

---

# 📚 Currently Learning

```text
Core Java & OOP
       │
       ▼
SOLID Principles
       │
       ▼
Design Patterns
       │
       ▼
Clean Architecture
       │
       ▼
Spring Boot
       │
       ├── REST APIs
       ├── Security
       └── Microservices
       │
       ▼
System Design
       │
       ├── Scalability
       ├── Database Design
       ├── Caching
       ├── Load Balancing
       └── Distributed Systems
```

My current focus is moving beyond simply **building applications** toward understanding **how to design systems that remain maintainable and scalable as complexity grows**.

---

# 📌 Other Projects

Some of my other work includes:

* 🗃️ **Inventory Management System**
* 🛒 **E-Commerce Backend Projects**
* ☕ **Java Applications**
* 🧩 **DSA Practice & Problem Solving**

🔗 **[Explore all repositories →](https://github.com/karanjot140506?tab=repositories)**

---

# 🎯 Developer Philosophy

```java
while (true) {
    Learn();
    Build();
    Solve();
    Improve();
}
```

> **Don't just write code. Understand the system behind it.**

---

# 🤝 Let's Connect

I'm interested in connecting with developers and engineers who enjoy building software, discussing backend architecture, and learning how large-scale systems work.

<p align="left">
  <a href="https://www.linkedin.com/in/karanjot-singh-172bb3286">
    <img src="https://img.shields.io/badge/LinkedIn-Karanjot%20Singh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/karanx/">
    <img src="https://img.shields.io/badge/LeetCode-Karanx-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://github.com/karanjot140506">
    <img src="https://img.shields.io/badge/GitHub-Karanjot%20Singh-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <i>Building backend systems. Learning system design. Improving every day.</i>
</p>


<!--
**karanjot140506/karanjot140506** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
