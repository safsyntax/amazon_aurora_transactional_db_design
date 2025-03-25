# 🗄️ Transactional Database Design with Amazon Aurora

This project showcases the design and implementation of a scalable and ACID-compliant transactional database system using **Amazon Aurora**. Built to manage over **1.1 million e-commerce transactions**, the database ensures efficient CRUD operations, strong data integrity, and performance consistency in high-throughput environments.

## 📌 Project Overview

Reliable data storage and transaction handling are critical in e-commerce systems where even small inconsistencies can impact user trust and financial accuracy. This project uses **Amazon Aurora (MySQL-compatible)**, a cloud-native relational database engine that combines the performance of high-end commercial databases with the simplicity and cost-effectiveness of open-source databases.

## 🔧 Tools & Technologies

- **Database Engine**: Amazon Aurora (MySQL-compatible)
- **Cloud Platform**: AWS RDS (Relational Database Service)
- **Languages**: SQL, Python (for database connectivity)
- **Libraries**: `SQLAlchemy`, `PyMySQL`, `pandas`

## 🧠 Key Features

### 1. Schema Design
- Structured the database to support a transactional e-commerce system with:
  - **Primary Keys** for uniqueness
  - **Foreign Keys** for referential integrity
  - **Composite Keys** for complex relationships
- Emphasized normalization and modular table design for scalability and clarity.

### 2. CRUD Operations
- Developed and executed **Create, Read, Update, and Delete** operations.
- Optimized query performance for large datasets.
- Handled edge cases to ensure system robustness.

### 3. ACID Compliance
- Implemented transaction control to ensure:
  - **Atomicity**: All-or-nothing operations
  - **Consistency**: Valid data at every state
  - **Isolation**: Concurrent transaction safety
  - **Durability**: Data persistence after commit

### 4. Scalability & Performance
- Designed with **over 1.1 million records** in mind.
- Leveraged **Amazon Aurora’s** high throughput and replication capabilities to manage large-scale data securely and efficiently.

## 📁 Repository Contents

- [`crud_statements`](https://github.com/safsyntax/amazon_aurora_transactional_db_design/blob/7072c3aaa674db883586380f10aab975ff43c27e/crud_statements): Contains SQL scripts used to create tables, insert data, and perform CRUD operations.

## 🚀 Future Enhancements

- Implement stored procedures and triggers for automation.
- Develop a front-end dashboard for real-time transaction monitoring.
- Integrate API endpoints for web or mobile use.
- Add role-based access control (RBAC) for improved security.

## 💡 Use Case

This database architecture can be adapted to real-world e-commerce applications such as:
- Order management systems
- Inventory tracking platforms
- Customer relationship management (CRM)
- Payment processing and transaction logs

## 📬 Contact

For feedback, questions, or collaboration opportunities, reach out via [GitHub](https://github.com/safsyntax) or connect on [LinkedIn](https://www.linkedin.com/in/safiya-joseph-39248b51).
