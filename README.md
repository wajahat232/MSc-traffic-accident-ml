# AI-Based Traffic Accident Severity and Hotspot Prediction Using Machine Learning

This repository contains the implementation code for an MSc Computer Science dissertation
submitted to Birmingham City University.

The project focuses on predicting road traffic accident severity and identifying spatial
accident hotspots using machine learning and spatial clustering techniques applied to UK
road traffic accident data.

---

## Project Overview

Road traffic accidents remain a major public safety concern in the United Kingdom.
This project proposes an integrated data-driven framework that combines supervised
machine learning models for accident severity prediction with unsupervised clustering
for spatial hotspot detection.

The study is based on the UK STATS19 road accident dataset published by the Department
for Transport (DfT).

---

## Methods and Techniques

The following techniques are implemented in this project:

- Data preprocessing and feature encoding
- Accident severity prediction using:
  - Random Forest
  - XGBoost
- Spatial accident hotspot detection using:
  - DBSCAN clustering
- Visualisation of prediction results and hotspot patterns

Tree-based ensemble models were selected due to their robustness and suitability for
structured accident data, while DBSCAN was chosen for its ability to detect dense spatial
clusters without requiring a predefined number of clusters.

---

---

## Dataset

The dataset used in this project is the **UK STATS19 Road Accident Dataset**, which is
publicly available from the UK Department for Transport.

Due to the large size of the dataset, it is **not included in this repository**.

### Dataset Source
https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data

### How to Use the Dataset
1. Download the STATS19 accident data from the link above.
2. Extract the relevant CSV file(s).
3. Place the dataset in a local `data/` directory.
4. Update the dataset file path in the notebooks if required.

---

## Notes

- No personal or sensitive data is included in this repository.
- All data used is publicly available.
- The notebooks are provided without outputs to maintain a lightweight and reproducible repository.
- All results and analysis are documented in the accompanying dissertation report.



## Repository Structure

