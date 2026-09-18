# Gold Volatility & Price Trend Data Pipeline 🟡

An open-ended portfolio project completed to graduate from the **Data and Programming Foundations for AI** skill path. This project engineers an off-platform data ingestion, wrangling, and exploratory analysis pipeline designed to prepare historical financial asset profiles for predictive machine learning models.

## 🎯 Project Objectives
* Scope and execute an independent data analysis problem from scratch.
* Ingest market asset sheets locally using **VS Code** and **Jupyter Notebooks**.
* Wrangle granularity inconsistencies and handle structural missing (`NaN`) values via directional forward-filling.
* Engineer downstream Machine Learning pipeline features: rolling moving averages, absolute intraday volatility bands, and binary movement classification labels.

## 📊 Data Attribution & Licensing
* **Dataset Used:** Gold Price Dataset (2016-2026) by Abdul Malik Lodhra via Kaggle.
* **Licensing Compliance:** Distributed under [CC BY-SA 4.0](https://creativecommons.org). This project complies with Attribution-ShareAlike requirements by publishing the transformed data structure and programmatic codebase under identical open-source terms.

## 📈 Engineering Insights Summary
* **Pipeline Output:** Successfully wrangled raw price arrays into clean, synchronized timelines, engineering rolling volatility baseline profiles.
* **ML Readiness:** The generated binary destination matrix (`ML_Target`) provides the foundational inputs required to train classification models in the upcoming AI Engineer career modules.
