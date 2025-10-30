# 📈 Portfolio Optimization and Risk Analysis

**Author:** Enrique Ruiz de Almirón Da Silva  
**Objective:** Build, optimize, and evaluate multi-asset portfolios using modern portfolio theory, Monte Carlo simulations, and factor/risk-based validation.

---

## 🧩 Project Structure

1. **Data Loading and Selection**  
2. **Log Returns Calculation**  
3. **Covariance Matrix Estimation**  
4. **Portfolio Analytics Functions**  
5. **Risk-Free Rate Retrieval**  
6. **Portfolio Constraints and Mandates**  
7. **Portfolio Optimization — Constraints and Setup**  
8. **Tangency Portfolio Optimization & Metrics** *(ongoing ⚠️)*  
9. **Benchmarking**  
10. **Portfolio Risk & Stress Testing**  
11. **Brinson Attribution** *(ongoing ⚠️)*  
12. **Fama-French Factor Analysis** *(ongoing ⚠️)*  

---

## ⚠️ Disclaimer

This notebook forms part of an **independent research project** on portfolio optimization and factor analysis.  
The repository’s goal is to:
- Document my **learning process** in quantitative finance,  
- Demonstrate my ability to **structure research workflows**, and  
- Track progress as I refine both **technical and conceptual understanding**.

> The work is **in progress** and may include:
> - Interpretation inaccuracies  
> - Data alignment issues  
> - Code inefficiencies  
> - Inconsistencies in presentation  

Its **primary purpose is educational and exploratory**, serving as a framework for continuous improvement rather than an operational trading system.  
I am gradually enhancing the methodology, documentation, and clarity of insights as I deepen my understanding of quantitative finance and data modeling.

---

## 🧠 Methodology Overview

This notebook presents a **static portfolio optimization framework** based on *Modern Portfolio Theory (Markowitz, 1952)*, aimed at demonstrating the **end-to-end quantitative workflow** — from data collection and risk estimation to portfolio construction, validation, and performance attribution.

In institutional asset management, portfolio optimization is typically performed on a **rolling or walk-forward basis**, where portfolio weights are re-optimized periodically using only past data.

Implementing a full rolling optimization and backtesting pipeline is **beyond the scope** of this initial version, but future iterations will incorporate:

- Rolling (walk-forward) re-optimization and out-of-sample testing  
- Rebalancing frequency sensitivity analysis  
- Transaction cost integration and turnover control  

For the current version, the focus remains on understanding the **mechanics, limitations, and validation** of the static mean-variance framework, complemented with **robust evaluation techniques** (bootstrapping, stress testing, and factor attribution).

---

## 🧭 Future Improvements
- Modularize functions and improve code readability  
- Enhance visualization (Sharpe distribution, frontier curvature)  
- Add VaR / CVaR Monte Carlo simulations  
- Integrate factor-based validation (Fama-French, Brinson)

---

## 📘 License
MIT License © 2025 Enrique Ruiz de Almirón Da Silva
