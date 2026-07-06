# 🌍 GIS-Based Identification of Water Harvesting and Groundwater Recharge Sites using GIS and Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![QGIS](https://img.shields.io/badge/QGIS-3.x-green)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Project Overview

Groundwater plays a crucial role in sustaining agriculture in mountainous regions such as the Himalayas. Identifying suitable groundwater recharge zones using conventional field surveys is often time-consuming and resource-intensive.

This project integrates **Geographic Information Systems (GIS)**, **Remote Sensing**, and **Random Forest Machine Learning** to identify groundwater recharge suitability zones within the **Sainji Watershed, Tehri Garhwal, Uttarakhand**.

The project demonstrates how spatial datasets derived from GIS can be combined with machine learning techniques to model groundwater recharge suitability and support sustainable water resource management.

---

## 🎯 Project Objectives

- Delineate the watershed using Digital Elevation Model (DEM)
- Generate thematic layers influencing groundwater recharge
- Produce a groundwater recharge suitability map using weighted overlay analysis
- Train a Random Forest Regression model using GIS-derived variables
- Evaluate model performance using standard regression metrics
- Interpret the contribution of each environmental factor through feature importance analysis

---

## 📍 Study Area

**Village:** Sainji

**District:** Tehri Garhwal

**State:** Uttarakhand, India

The study focuses on a small Himalayan watershed surrounding Sainji village, characterized by complex topography and predominantly agricultural land use.

---

## 🛰️ Data Sources

| Dataset | Purpose |
|----------|----------|
| DEM | Elevation, Slope, Watershed Delineation |
| Sentinel-2 | Land Use / Land Cover |
| NASA POWER | Rainfall |
| Stream Network | Derived from DEM |
