# 🛡️ System Threat Forecaster

This repository contains my solution for the [System Threat Forecaster](https://www.kaggle.com/competitions/system-threat-forecaster) Kaggle competition. The goal of the challenge is to forecast cybersecurity threats based on system activity logs using machine learning.

---

## 📌 Project Overview

The competition focuses on predicting the severity of potential system threats from activity logs. This involves:
- Cleaning and feature engineering from raw log data
- Modeling using various ML algorithms
- Evaluating performance using competition-specific metrics

---

## Approach

### Preprocessing
- Data cleaning
- Timestamp conversion & extraction of time-based features
- Categorical encoding

### Feature Engineering
- Aggregations by IP/User/Time
- Behavioral pattern recognition
- Threat indicator scoring

### Models Used
- XGBoost
- LightGBM
- CatBoost
- Ensemble blending

---

## 📁 File Structure

```plaintext
system-threat-forecaster/
├── System Threat Forecaster.ipynb   # Main notebook
├── image.png                        # Model diagram / results visualization
├── requirements.txt                 # Environment dependencies
├── README.md                        # Project overview
└── LICENSE                          # License file (MIT recommended)
```

 ### 1. Clone the repo
```bash
git clone https://github.com/srama-krishnan/system-threat-forecaster.git
cd system-threat-forecaster
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Kaggle & organizers for the competition
Open-source tools & the Kaggle community


### Run the Notebook
Open System Threat Forecaster.ipynb with Jupyter or VSCode to explore the project.
