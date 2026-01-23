# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Exploring Female Autism Referral Trends in England
An NHS Open Data Analysis


## Project Overview

This project analyses publicly available NHS England autism statistics to explore female autism referral trends over time. It focuses on identifying temporal patterns and age-group differences in referrals and open cases, using an end-to-end data analysis pipeline and both static and interactive visualisations.

The project was developed as a custom data analysis capstone and demonstrates structured data extraction, cleaning, transformation, exploratory analysis, and visual communication.


## Project Motivation

Autism has historically been under-recognised in females, partly due to diagnostic criteria and clinical understanding being shaped around male presentations. This has contributed to delayed or missed diagnoses, with significant consequences for wellbeing, education, and access to support.

By analysing NHS open data on autism referrals, this project aims to examine whether female referral patterns show distinct trends over time and across age groups, and to consider what these trends may suggest about visibility, service demand, and diagnostic pathways within England.


## Objectives

- Build a reproducible ETL pipeline to extract, clean, and structure NHS autism data
- Analyse temporal trends in female autism referrals and open cases
- Examine age-group patterns within female referral data
- Develop static and interactive visualisations to communicate insights
- Critically reflect on limitations and ethical considerations when working with public healthcare data


## Project Hypotheses

H1: Female suspected autism referrals show an overall increasing trend over time, indicating rising demand and/or improved recognition.

H2: The number of females with open suspected autism referrals remains consistently higher than new referrals, suggesting backlog pressure within diagnostic pathways.

H3: Age-group patterns differ within females, with 0–17 and 18+ showing distinct referral volumes, supporting the need for age-targeted service planning.


## Project Structure 

sum-1/
│
├── data/
│   ├── raw/                 # Original NHS dataset
│   └── processed/          # Cleaned and transformed datasets
│
├── jupyter_notebooks/
│   └── Notebook_Template.ipynb   # Main analysis notebook
│
├── reports/
│   └── female_autism_dashboard.html   # Interactive Plotly dashboard
│
├── requirements.txt
├── README.md
└── .gitignore


## Tools & Technologies

- Python 3.11
- Pandas: data manipulation and cleaning
- NumPy:  numerical operations
- Matplotlib & Seaborn: static visualisations
- Plotly: interactive dashboard
- Jupyter Notebook: analysis environment
- VS Code: development environment


## Use of Generative AI (GenAI) in this Project

GenAI (CoPilot) was used to support the workflow:
1. **Code support and debugging:** assisting with troubleshooting environment issues (VS Code/Jupyter/Plotly rendering) and improving the reliability of file outputs (e.g., ensuring folders exist before writing HTML).
2. **Data storytelling and communication:** refining the project title, motivation, objectives, and writing clear interpretations of each chart for a non-technical audience.


## How to Run the Project

1) Clone or download the repository
2) Create and activate a virtual environment
3) Install dependencies:
pip install -r requirements.txt
4) Open the notebook:
jupyter notebook jupyter_notebooks/Notebook_Template.ipynb
5) Run all cells from top to bottom. The interactive dashboard will be saved to:
reports/female_autism_dashboard.html
Open this file in any web browser to view the interactive plot.


## Outputs

- Cleaned and structured analytical dataset
- Exploratory and descriptive statistics
- Static plots of distributions, trends, and comparisons
- Interactive Plotly time-series dashboard
- Fully documented Jupyter Notebook with methodology and interpretation


## Limitations and Ethics

This project uses aggregated NHS referral data rather than individual-level records. The dataset reflects referrals and open cases, not confirmed diagnoses, and does not include demographic variables such as ethnicity or deprivation indices within this extract.

All data is fully anonymised and publicly available. Care has been taken to frame findings at a systems level and to avoid stigmatising interpretations.


## Future Work

Future extensions could:
- Integrate datasets containing ethnicity and deprivation indices
- Incorporate confirmed diagnostic outcomes
- Explore regional variation in referral patterns
- Expand the interactive dashboard for stakeholder-focused reporting


## Author

Shazia 
Custom Data Analysis Capstone Project – January 2026