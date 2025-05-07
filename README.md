# 🔄 API to MySQL Data Integration with Python

This project demonstrates a simple ETL (Extract, Transform, Load) pipeline that fetches user data from a public JSON API, transforms it into a structured format using Python, and loads it into a MySQL database.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [What is ETL?](#-what-is-etl)
- [Data Source](#-data-source)
- [Project Structure](#-project-structure)
- [Setup Instructions](#-setup-instructions)
- [Running the Pipeline](#-running-the-pipeline)
- [Sample Output](#-sample-output)
- [Technologies Used](#-technologies-used)
- [Next Steps](#-next-steps)
- [License](#-license)
- [Connect](#-connect)

---

## 🚀 Project Overview

This mini-project covers the full lifecycle of a data integration flow:

1. **Extract** – Fetch raw JSON data from an API
2. **Transform** – Flatten nested fields, clean column names, and create derived fields
3. **Load** – Insert the cleaned data into a MySQL database using SQLAlchemy

The goal is to simulate a real-world pipeline that ingests API data into a relational database for further analysis or reporting.

---

## 📚 What is ETL?

ETL stands for **Extract, Transform, Load**:
- **Extract**: Collect data from sources like APIs, CSVs, databases
- **Transform**: Clean, normalize, and enrich data to match business needs
- **Load**: Store the processed data into target systems like SQL databases or data warehouses

---

## 🔗 Data Source

We are using the free, public API provided by [JSONPlaceholder](https://jsonplaceholder.typicode.com/users), which returns mock user data in JSON format.

---

## 🗂 Project Structure
