# Haier-Europe-2025-Datathon
This notebook presents my solution for the Haier Europe Sell-In Forecasting Datathon 2025, focusing on 12-month demand forecasting at SKU and category levels. The approach uses Prophet-based time series models with lifecycle-aware logic and time-based validation to deliver stable, business-ready forecasts. Achieved 5th place overall.

📦 Haier Europe Sell-In Demand Forecasting – Datathon 2025
🧠 Project Overview
This repository contains my solution developed for the Haier Europe Sell-In Forecasting Datathon 2025, where the objective was to predict 12-month future demand at both SKU and category levels using real-world sales data.
The project focuses on:
Accurate long-term demand forecasting
Handling product lifecycle dynamics (new, active, and phasing-out SKUs)
Designing a production-ready forecasting pipeline suitable for real business operations
The solution achieved 2nd place overall among 74 teams and 98 participants.
🎯 Problem Statement
Forecast future monthly sell-in quantities for Haier Europe products by:
Modeling seasonality and trend patterns
Managing sparsity and zero-sales periods
Addressing SKU lifecycle behavior (especially end-of-life products)
Evaluation metrics focused on forecast accuracy and stability across multiple hierarchical levels.
⚙️ Methodology
The final approach combines time-series modeling and ensemble techniques:
Facebook Prophet for capturing:
Seasonality
Trend changes
Holiday effects
Segment-level modeling (SKU / Category based)
Lifecycle-aware logic for phasing-out products
Post-processing adjustments to improve stability and reduce bias
Key techniques:
Time-based cross-validation
Multi-seed averaging
Thresholding & bias correction
Hierarchical consistency checks
📊 Results
5nd place on Kaggle leaderboard
5nd place in final jury presentation
Strong performance in long-horizon forecasts
Robust behavior for sparse and low-volume SKUs
