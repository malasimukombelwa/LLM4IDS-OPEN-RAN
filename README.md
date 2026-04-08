# Semantic-Aware IDS Pipeline for Open RAN and Network Security

A semantic-aware intrusion detection pipeline designed for cybersecurity experimentation across conventional network traffic and Open RAN environments. This project focuses on dataset inspection, preprocessing, stratified sampling, and experimentation using three representative datasets: **UNSW-NB15**, **CICIDS2017**, and **OpenIreland**.

---

## Overview

Intrusion Detection Systems (IDS) remain essential for protecting modern communication infrastructures. However, the evolution toward **Open RAN** introduces new security challenges due to increased openness, programmability, and modularity.

This project provides a practical notebook-based pipeline for:

- exploring cybersecurity datasets,
- identifying label columns automatically,
- analyzing class distributions,
- generating stratified subsets,
- preparing data for semantic-aware IDS experiments.

The goal is to support reproducible research in both **traditional network intrusion detection** and **Open RAN security analysis**.

---

## Datasets

This notebook supports experiments on the following datasets:

- **UNSW-NB15**  
  A widely used benchmark dataset for modern network intrusion detection.

- **CICIDS2017**  
  A realistic intrusion detection dataset containing benign traffic and multiple attack scenarios.

- **OpenIreland**  
  An Open RAN-oriented dataset used for analyzing security behavior in programmable radio access network environments.

These datasets provide complementary perspectives for evaluating IDS performance across heterogeneous cybersecurity contexts.

---

## Main Features

- automatic label column detection
- dataset shape and structure inspection
- class distribution analysis
- normalized label distribution
- descriptive statistics for numerical features
- label visualization with bar plots
- stratified sampling for balanced subsets
- saving processed subsets as CSV files
- support for rapid experimentation in Google Colab

---

## Repository Structure

```text
.
├── semantic_aware_ids_pipeline_unsw_nb15_cicids2017_openireland.ipynb
├── README.md
├── data/
│   ├── raw/
│   └── subsets/
├── figures/
└── requirements.txt
