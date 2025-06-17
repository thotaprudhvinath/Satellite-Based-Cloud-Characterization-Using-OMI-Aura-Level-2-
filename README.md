# 🌥️ Satellite-Based Cloud Characterization Using OMI-Aura Level-2 HDF-EOS5 Data for Atmospheric Analysis

## 📌 Project Overview

This project focuses on the **spatiotemporal analysis of cloud behavior** using satellite-derived atmospheric parameters. Leveraging NASA's **OMI-Aura Level-2 Cloud Product**, we aim to analyze cloud fraction, reflectivity, and pressure over time and space to enhance our understanding of atmospheric dynamics.

The study spans **OMI satellite data from 2020 to 2024**, including the leap year 2020, and projects findings to **May 2025**. The work involves data preprocessing, visualization, and machine learning modeling for temporal trend prediction.

---

## ❓ Research Question

**How can satellite-derived atmospheric parameters such as cloud fraction, reflectivity, and pressure be integrated and analyzed to understand spatiotemporal cloud behavior over specific regions?**

---

## 🛰️ Dataset Information

- **Dataset Name:** OMI-Aura Level-2 Cloud Product  
- **Format:** HDF-EOS5  
- **Data Type:** Tabular scientific data with 2D continuous numerical arrays  
- **Variables:**  
  - Cloud fraction  
  - Cloud pressure  
  - Cloud optical centroid pressure  
  - Reflectivity  
  - Geolocation: latitude, longitude  
  - Solar and viewing angles  

- **Temporal Coverage:** January 2020 – December 2024  
- **Future Projection:** May 2025  

### 🌍 Source

- **Organization:** NASA Earthdata  
- **Satellite:** Aura (launched July 2004)  
- **Instrument:** Ozone Monitoring Instrument (OMI)  
- **URL:** [https://earthdata.nasa.gov/](https://earthdata.nasa.gov/)

---

## 🔧 Technologies Used

- **Programming Language:** Python  
- **Libraries:**  
  - `h5py`, `netCDF4` for reading HDF-EOS5 files  
  - `numpy`, `pandas` for data processing  
  - `matplotlib`, `seaborn`, `plotly` for visualization  
  - `scikit-learn`, `XGBoost`, `TensorFlow` for modeling  
- **Environment:** Google Colab  
- **Data Access:** NASA Earthdata Login API

---

## 📈 Project Workflow

1. **Data Retrieval:**  
   Download OMI-Aura Level-2 Cloud data (2020–2024) from NASA Earthdata.

2. **Data Preprocessing:**  
   Parse and convert HDF-EOS5 arrays into structured tabular format.

3. **Feature Engineering:**  
   Extract geospatial and atmospheric parameters for analysis.

4. **Exploratory Data Analysis (EDA):**  
   Visualize seasonal and annual variations in cloud metrics.

5. **Spatiotemporal Modeling:**  
   - Apply regression and time-series models  
   - Forecast atmospheric parameters for May 2025  

6. **Interpretation and Reporting:**  
   - Identify regional patterns  
   - Discuss implications for atmospheric science  

---

## 📊 Example Visualizations

> _To be updated with plots like:_  
- Global cloud fraction heatmaps  
- Time-series trends  
- Region-specific variability comparisons

---

## 📁 Project Structure (Planned)

OMI-Cloud-Analysis/
├── data/
│   └── raw/              # HDF-EOS5 files
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_modeling.ipynb
├── src/
│   └── utils.py
├── outputs/
│   ├── figures/
│   └── models/
├── README.md
└── requirements.txt

---

## 🔓 Licensing & Acknowledgements

- Data provided by **NASA Earthdata** under open government license.  
- Special thanks to the **Aura/OMI science team** for continued satellite operations and public data access.

---
  
<!-- Add your contact links here -->
