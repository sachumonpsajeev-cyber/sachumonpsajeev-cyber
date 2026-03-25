# Hi, I'm Sachu Mon Puthenpuraickkal Sajeev👋

**MSc Data Science & Artificial Intelligence** | TSI University, Riga, Latvia  
**Research Focus:** Clinical Machine Learning · Deep Learning · Healthcare AI  
**Background:** BI & Data Visualization → HR & Talent Acquisition → Career transition into Data Science & AI  

I build machine learning systems that work on real, messy clinical data — currently focused on predicting life-threatening intraoperative events using physiological time-series.

📍 Riga, Latvia &nbsp;|&nbsp; [![WhatsApp](https://img.shields.io/badge/WhatsApp-+371%2022447242-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/37122447242) &nbsp;|&nbsp; 📬 [St87014@students.tsi.lv](mailto:St87014@students.tsi.lv) &nbsp;|&nbsp; 📬 [sachumonsajeevp3110@gmail.com](mailto:sachumonsajeevp3110@gmail.com) &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/sachu-mon)

---

## 👨‍💻 About Me

- 🎓 Currently completing **MSc Data Science & AI** at TSI University, Riga
- 🔬 Thesis: Predicting intraoperative cardiac arrest using Temporal Attention Networks on VitalDB clinical data
- 📊 Previously worked as a **Data Visualization Expert** (Power BI, Tableau, DAX) across BYJU'S and Testalogix Solutions — BI development, KPI validation, and data quality
- 🏢 Also experienced in **HR & Talent Acquisition** — full-cycle recruitment across India
- 🤖 Completed **Accenture Data Platform Bootcamp 2026** — hands-on training in AWS, Docker, Kubernetes, Cognigy.AI, Jenkins, Cybersecurity and more
- 🌍 Based in Riga, Latvia — open to relocation with visa sponsorship
- 💡 Passionate about applying AI to solve real-world healthcare problems

---

## 🔬 MSc Thesis — Intraoperative Cardiac Arrest Prediction

> **Multi-Window Cardiac Arrest Prediction Using Temporal Attention Networks on VitalDB Clinical Time-Series**

Developed a two-stage deep learning pipeline to predict intraoperative cardiac arrest (CA) at 30, 60, 120, and 240 minutes before the event, using the publicly available VitalDB dataset (6,388 perioperative surgical cases).

| Component | Detail |
|---|---|
| **Dataset** | VitalDB — 6,388 perioperative cases, Seoul National University Hospital |
| **Signals** | Heart rate, SpO₂, EtCO₂, MAP, SBP, DBP (36-dimensional feature vector) |
| **Architecture** | TAN-LSTM hybrid (4-head self-attention + LSTM ensemble) |
| **Best Result** | AUROC 0.9180 (95% CI: 0.8944–0.9405) on multi-window sub-cohort |
| **Baselines** | LightGBM · Random Forest · XGBoost · Logistic Regression · LSTM |
| **Class Imbalance** | 1:26 to 1:96 → handled with Focal Loss, class-balanced weighting, Youden's J |
| **Validation** | 5-fold cross-validation, bootstrap DeLong test (p < 0.05) |

📁 [View the project repository →](https://github.com/sachumonpsajeev-cyber/VitalDb-Cardiac-Arrest-Prediction-TAN)

---

## 🏢 Accenture Data Platform Bootcamp 2026

> One-month intensive hands-on bootcamp covering cloud, DevOps, AI and data engineering

| Week | Focus |
|---|---|
| **Week 1** | AWS Advanced · S3 · Cloud Computing · Networking |
| **Week 2** | Python · SQL · HTML · YAML · Git |
| **Week 3** | Docker · Kubernetes · Jenkins CI/CD |
| **Week 4** | Cognigy.AI Chatbot · Cybersecurity · Final Projects |

🏆 Certificate: *Awaiting issuance — completed February 27, 2026*

📁 [View bootcamp repository →](https://github.com/sachumonpsajeev-cyber/accenturebootcamptasks)

---

## 🗂️ Featured Projects

### 🫀 [VitalDB Cardiac Arrest Prediction — TAN](https://github.com/sachumonpsajeev-cyber/VitalDb-Cardiac-Arrest-Prediction-TAN)
Intraoperative cardiac arrest prediction using a novel Temporal Attention Network (TAN) + LSTM hybrid architecture on VitalDB clinical time-series data. Includes full preprocessing pipeline, multi-window feature engineering, and model evaluation across four temporal horizons.  
`Python` `PyTorch` `LightGBM` `Scikit-learn` `VitalDB`

---

### 🧠 [Physiological Signal-Based Stress Prediction](https://github.com/sachumonpsajeev-cyber/Physiological-Signal-Based-Stress-Prediction)
End-to-end ML pipeline for classifying psychological stress states from raw physiological signals. Covers feature extraction, model training, and comparative evaluation of classification algorithms.  
`Python` `Scikit-learn` `Pandas` `Jupyter`

---

### 🔷 IBM HR Attrition Analytics — Power BI
**`Power BI` `DAX` `Data Quality` `KPI Validation` `HR Analytics`**

A 3-page Power BI dashboard built on the IBM HR dataset (1,470 employees) with full DAX measure testing and data quality validation throughout.

**What I built & validated:**
- 5 DAX measures: Attrition Rate %, Attrited Employees, Active Employees, Avg Salary (Attrited), Overtime Attrition %
- Each measure cross-verified against raw data using SQL-style checks
- Identified and corrected Age Group bucketing logic errors before publishing
- Validated salary band segmentation and overtime filter accuracy across all visuals
- Tested all filter/slicer interactions and confirmed KPI consistency across all 3 pages

📁 [View Repository →](https://github.com/sachumonpsajeev-cyber/IBM-HR-Attrition-PowerBI)  
`Power BI` `DAX` `Excel` `Data Validation` `HR Analytics`

---

### 🟣 Airline Quality Rating Analysis — Tableau
**`Tableau` `Data Cleaning` `Dashboard Design` `KPI Analysis`**

Interactive Tableau dashboard analysing passenger satisfaction patterns across 129,880 airline passengers — built for the Business Intelligence & Data Visualization module, MSc Data Science & AI (TSI University / UWE Bristol, 2025).

**Dataset:** Airline Quality Ratings — Kaggle | **Tools:** Tableau Desktop · Microsoft Excel

**Dashboard includes:**
- KPI cards: Total Passengers · Avg Flight Distance · Avg Passenger Age · Avg Arrival & Departure Delay
- Donut chart — Overall satisfaction (56.55% Satisfied vs 43.45% Neutral/Dissatisfied)
- Bar chart — Satisfaction by passenger type (Business vs Personal)
- Column chart — Satisfaction by travel type (Business · Economy · Economy Plus)
- Grouped bar chart — Passenger info by age & class
- Stacked bar chart — Passenger choice by flight leg (Long / Medium / Short)
- Interactive filters — Customer Type · Gender · Type of Travel

**Data quality work done:**
- Identified null values, blank fields, and duplicate records in Excel before connecting to Tableau
- Cross-validated all KPI metrics against raw dataset to confirm accuracy
- Rebuilt data connection post-cleaning to ensure reliable and consistent visualisations
- Applied iterative design — layout, colour palette, and font decisions informed by Gestalt principles

📁 [View Repository →](https://github.com/sachumonpsajeev-cyber/Airline-Quality-Tableau)  
`Tableau` `Excel` `Data Cleaning` `Dashboard Design` `KPI Validation`

---

### ⚙️ [Model Building Workspace](https://github.com/sachumonpsajeev-cyber/model-building-workspace)
A centralised knowledge repository documenting my ML engineering learning journey — experiments, training modules, and technical notes across data science and AI topics.  
`Python`

---

### ☁️ [AWS S3 Static Hosting](https://github.com/sachumonpsajeev-cyber/sachu-s3-bucket)
Hands-on project deploying a static website using AWS S3 bucket configuration — part of cloud infrastructure practice from Accenture bootcamp.  
`HTML` `AWS`

---

### 📋 [Accenture Data Platform Bootcamp](https://github.com/sachumonpsajeev-cyber/accenturebootcamptasks)
Assignments and projects from the Accenture Data Platform Bootcamp 2026 — covering AWS, Docker, Kubernetes, Cognigy.AI chatbot, Jenkins, cybersecurity and more.  
`Python` `AWS` `Docker` `Kubernetes` `Cognigy.AI` `Shell`

---

## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logoColor=white)
![Shell](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**ML / DL Frameworks**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat&logoColor=white)

**Data & Visualisation**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logo=powerbi&logoColor=black)

**Cloud & DevOps**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**BI & Data Quality**  
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

**AI & Tools**  
![Cognigy](https://img.shields.io/badge/Cognigy.AI-7B2FBE?style=flat&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)

---

## 📬 Get in Touch

🟢 **Open to:** Full-time roles · Part-time positions · Research collaborations · Visa-sponsored opportunities  
💡 **Interests:** Clinical AI · Healthcare Data Science · Machine Learning Engineering · BI & Data Quality · Data Science  
🌍 **Location:** Riga, Latvia — open to relocation with visa sponsorship

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sachu-mon)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/37122447242)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Sachumonsajeevp3110@gmail.com)
