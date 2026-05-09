# Empowering Women Entrepreneurs through Blockchain
### A Decentralized Framework for Financial Transformation in SMEs

This repository contains the research and Python implementation of a blockchain-based credit scoring framework designed to reduce gender bias in lending.

---

## 📌 Project Overview
Traditional financial systems often exclude women entrepreneurs due to opaque decision processes. This project proposes a decentralized alternative using a weighted composite credit score based on:
* **Reputation Score**: Historical reliability.
* **Revenue Stability Score**: Consistency of business income.
* **Digital Trust Flag**: Verified digital transaction participation.

## ⚙️ Technical Implementation
The simulation (found in `assignment_4.ipynb`) replicates four core blockchain properties:

1. **Immutability**: SHA-256 hashing ensures data cannot be tampered with.
2. **Decentralization**: The dataset is processed across three virtual nodes.
3. **Consensus**: A **2-of-3 majority vote** system determines loan eligibility.
4. **Transparency**: A generated `audit_log.csv` records all hashed decisions.

## 📊 Experimental Results
The blockchain consensus system was tested against a 1,000-record dataset and showed significant improvements over traditional single-node systems:

| Metric | Blockchain System | Single-Node Baseline |
| :--- | :--- | :--- |
| **Accuracy** | **66.7%** | 55.3% |
| **Precision** | **87.5%** | 84.0% |
| **Recall** | **67.6%** | 53.8% |
| **F1-Score** | **76.3%** | 65.6% |


---
**Author:** Yumna Aamer  
**Institution:** National University of Computer and Emerging Sciences (FAST-NUCES)  
**Location:** Islamabad, Pakistan
