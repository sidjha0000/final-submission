# 📆 Dynamic Pricing for Urban Parking Lots

Capstone Project – Summer Analytics 2025

---

## 🌍 Overview

This project implements a **Dynamic Pricing System** for 14 urban parking lots using real-time data. The objective is to optimize space utilization by adjusting prices based on:

- Occupancy rate
- Queue length
- Traffic conditions
- Vehicle type
- Special event days

---

## ⚖️ Tech Stack

- **Python**
- **Pandas**, **NumPy** – data handling
- **Matplotlib** – visualization
- **Jupyter Notebook** – development environment
- **GitHub** – version control

---

## 🧠 Architecture Diagram

```mermaid
graph TD
    A[Input CSV Dataset (73 days)] --> B[Data Cleaning & Preprocessing]
    B --> C[Feature Engineering: Occupancy Rate, Vehicle Weights]
    C --> D[Model 1: Baseline Pricing]
    C --> E[Model 2: Demand-Based Pricing]
    D --> F[Price Clipping (5$-20$)]
    E --> F
    F --> G[Data Visualization]
    G --> H[Final Report & GitHub Submission]
