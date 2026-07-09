# 🚀 SpaceX Falcon 9 Data Science Capstone

**Applied Data Science Capstone Project** - IBM Data Science Professional Certificate

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=flat-square&logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical-lightblue?style=flat-square&logo=numpy)](https://numpy.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-green?style=flat-square&logo=scikit-learn)](https://scikit-learn.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-purple?style=flat-square&logo=plotly)](https://plotly.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

---

Capstone project in data science applied to the analysis of SpaceX's Falcon 9 launches, using data analysis and machine learning techniques to predict the success of the first-stage landing.

---

## Table of Contents

- [Project Overview](#project-overview)
- [About the Course](#about-the-course)
- [Project Structure](#project-structure)
- [Learning Path](#learning-path)
- [Installation & Setup](#installation--setup)
- [Jupyter Notebooks](#jupyter-notebooks)
- [Interactive Dashboard](#interactive-dashboard)
- [Key Findings](#key-findings)
- [Machine Learning Models](#machine-learning-models)
- [License](#license)
- [Author](#author)

---

## Project Overview

This project analyzes SpaceX's Falcon 9 launches to predict the success of the first-stage landing. Through a comprehensive data science workflow—from data collection and web scraping to exploratory analysis and machine learning—this capstone demonstrates practical skills in modern data science tools and techniques.

**Key Highlights:**
- Data collection from REST APIs and web scraping
- Data wrangling with SQL and Python
- Exploratory data analysis with statistical insights
- Machine learning models for prediction
- Interactive Plotly Dash dashboard with real-time filtering
- Geographic analysis of launch sites

---

## About the Course

This project is the **Applied Data Science Capstone**, the final course of the **IBM Data Science Professional Certificate** and the **Applied Data Science with Python** specialization on Coursera.

**Course Details:**
- Platform: [Coursera - Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone)
- Provider: IBM
- Certification: IBM Data Science Professional Certificate
- Skills: APIs, Web Scraping, SQL, EDA, ML, Data Visualization, Dashboard Development

---

## Project Structure

```
SpaceX-Falcon9-DataScience-Capstone/
│
├── notebooks/                              # Jupyter Labs
│   ├── 01_jupyter-labs-spacex-data-collection-api.ipynb
│   ├── 02_jupyter-labs-webscraping.ipynb
│   ├── 03_labs-jupyter-spacex-Data wrangling.ipynb
│   ├── 04_jupyter-labs-eda-sql-coursera_sqllite.ipynb
│   ├── 05_eda-data-viz.ipynb
│   ├── 06_lab_jupyter_launch_site_location.ipynb
│   └── 07_SpaceX_Machine Learning Prediction_Part_5.ipynb
│
├── src/
│   └── spacex-app.py                      # Plotly Dash Dashboard
│
├── data/
│   ├── raw/                               # Original data
│   └── processed/                         # Cleaned data
│
├── results/
│   ├── plots/
│   ├── models/
│   └── reports/
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## Learning Path

| Phase | Notebook | Skills Covered |
|-------|----------|----------------|
| **1. Data Collection** | `01_jupyter-labs-spacex-data-collection-api.ipynb` | REST APIs, JSON parsing, data extraction |
| **2. Web Scraping** | `02_jupyter-labs-webscraping.ipynb` | BeautifulSoup, HTML parsing, data enrichment |
| **3. Data Wrangling** | `03_labs-jupyter-spacex-Data wrangling.ipynb` | Data cleaning, transformations, feature creation |
| **4. SQL & Database** | `04_jupyter-labs-eda-sql-coursera_sqllite.ipynb` | SQL queries, SQLite, data aggregation |
| **5. EDA & Visualization** | `05_eda-data-viz.ipynb` | Statistical analysis, Matplotlib, Seaborn |
| **6. Geographic Analysis** | `06_lab_jupyter_launch_site_location.ipynb` | Folium, location-based insights |
| **7. Machine Learning** | `07_SpaceX_Machine Learning Prediction_Part_5.ipynb` | Model training, evaluation, predictions |

---

## Installation & Setup

**Prerequisites:** Python 3.7+, pip

**Step 1: Clone the Repository**
```bash
git clone https://github.com/joes-mza/SpaceX-Falcon9-DataScience-Capstone.git
cd SpaceX-Falcon9-DataScience-Capstone
```

**Step 2: Create Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

**Step 3: Install Dependencies**
```bash
pip install -r requirements.txt
```

**Step 4: Launch Jupyter**
```bash
jupyter lab
```

---

## Jupyter Notebooks

Run notebooks in order for the complete workflow:

1. **Data Collection** - SpaceX API integration
2. **Web Scraping** - Enhanced data gathering
3. **Data Wrangling** - Clean and transform data
4. **SQL & Database** - Query and aggregate data
5. **EDA & Visualization** - Explore patterns and trends
6. **Geographic Analysis** - Launch site analysis
7. **Machine Learning** - Build prediction models

---

## Interactive Dashboard

**Plotly Dash Application** - Explore SpaceX data dynamically with interactive filters and real-time visualizations.

**Features:**
- Filter by launch site, mission type, payload class
- Real-time chart updates with Dash Callbacks
- ML model predictions integrated
- Geographic visualization of launch sites

**Run the Dashboard:**
```bash
python src/spacex-app.py
```

Then open your browser to: `http://127.0.0.1:8050`

---

## Key Findings

- Launch success rate improved from ~50% to ~80%+ over time
- Certain launch sites show higher success rates
- LEO (Low Earth Orbit) missions more successful than GEO
- Payload mass inversely correlates with landing success
- Experience and reusability positively impact outcomes

---

## Machine Learning Models

| Model | Type | Performance |
|-------|------|-------------|
| Logistic Regression | Linear Classification | Fast & Interpretable |
| Random Forest | Ensemble | High Accuracy |
| Gradient Boosting | Advanced Ensemble | Best Performance |
| Support Vector Machine | Kernel-based | Non-linear |

**Metrics:** Accuracy, Precision, Recall, F1-Score, AUC-ROC

---

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

## Author

**Josias Minza** ([@joes-mza](https://github.com/joes-mza))

GitHub: [SpaceX Falcon 9 Data Science Capstone](https://github.com/joes-mza/SpaceX-Falcon9-DataScience-Capstone)

---

## Resources

- [SpaceX Official API](https://docs.spacexdata.com/)
- [Kaggle SpaceX Dataset](https://www.kaggle.com/datasets/spacex-falcon-9-launches)
- [IBM Data Science Certificate](https://www.coursera.org/professional-certificates/ibm-data-science)
- [Plotly Documentation](https://plotly.com/)
- [Scikit-learn Guide](https://scikit-learn.org/)

---

**Status:** Complete ✅ | **Last Updated:** July 2026
