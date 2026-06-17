# Predictive Telemetry Analytics & Anomaly Detection for UAV Swarms

This repository contains a **Proof of Concept (PoC)** developed in Python for analyzing aerospace/satellite telemetry streams, optimizing ground segment data flows, and implementing automated Product Assurance (PA) metrics.

### 🛠️ Key Technical Features:
* **Signal & Noise Decomposition:** Utilizes **STL (Seasonal-Trend Decomposition using Loess)** to mathematically isolate drone/satellite carrier trends from periodic deterministic noise (e.g., propeller/motor vibrations).
* **Statistical Anomaly Detection:** Implements a lightweight, real-time $3\sigma$ (Three-Sigma) thresholding algorithm to detect high-frequency anomalies, signal interference, or hardware failures.
* **Quantitative Product Assurance (PA):** Dynamically calculates an **Operational Fleet Reliability KPI (%)**, translating raw signal analysis into actionable risk management reports for mission control centers.

_Developed in Python (Jupyter/Google Colab) using `statsmodels`, `scipy`, `pandas`, and `matplotlib`._
