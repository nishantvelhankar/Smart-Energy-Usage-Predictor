# Smart-Energy-Usage-Predictor
ML-based system for energy consumption prediction, anomaly detection, and appliance-level usage analysis with an interactive Streamlit dashboard.  Tech Stack: Python, Scikit-learn, Pandas, Streamlit, Matplotlib
## Overview

This project predicts residential energy consumption using multiple machine learning models and detects abnormal energy usage patterns through residual-based anomaly detection and rule-based wastage detection.

The system also provides appliance-level analysis, feature importance evaluation, and energy-saving recommendations through a Streamlit dashboard.

---

## Features

- Residential energy consumption forecasting
- Residual-based anomaly detection
- Appliance-level usage analysis
- Hybrid machine learning and rule-based wastage detection
- Feature importance analysis
- Interactive Streamlit dashboard
- Smart energy-saving recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib
- Joblib

---

## Machine Learning Models

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Hybrid Ensemble Model

---

## Project Workflow

1. Data preprocessing and cleaning
2. Feature engineering and transformation
3. Model training and evaluation
4. Cross-validation and model selection
5. Residual-based anomaly detection
6. Appliance-level root cause analysis
7. Dashboard visualization using Streamlit

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib streamlit joblib
```
---

## Running the Project
- Run the Streamlit Dashboard
- streamlit run dashboard_final.py
- Google Colab Deployment

The project was developed in Google Colab and deployed using LocalTunnel for public Streamlit access.

## Generated Files

- `energy_model.pkl` — Trained machine learning pipeline  
- `final_processed_data.csv` — Processed dataset  
- `model_results.csv` — Model evaluation results  
- `alerts.csv` — Detected anomaly alerts  

---

## Project Structure

```text
energy-dashboard/
│── dashboard_final.py
│── energy_model.pkl
│── final_processed_data.csv
│── model_results.csv
│── alerts.csv
│── notebook.ipynb
│── README.md
```

---

## Dashboard Capabilities

- Visualize energy consumption trends  
- Compare model performance  
- Detect abnormal energy spikes  
- Analyze appliance usage  
- Display smart recommendations  
- Forecast future energy consumption  

---

## Future Improvements

- Real-time IoT sensor integration  
- Advanced time-series forecasting  
- Cloud deployment  
- Explainable AI integration  

---

## Collaborators

- Annanya Kesharwani  
- Madhuri Wagh  
- Nishant Velhankar
- Veda Mall

GitHub Profiles:
- [@annanyak12](https://github.com/annanyak12)
- [@madhuriwagh1105](https://github.com/madhuriwagh1105)
- [@nishantvelhankar](https://github.com/nishantvelhankar)
- [@VM-221b](https://github.com/VM-221b)
