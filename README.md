# 🧠 The Impact of Daily Routine on Mental Health
### C-DE211: Data Analysis — Project 3 | Spring 2026
**Egypt University of Informatics — Faculty of Computing & Information Sciences**

---

## 📋 Project Overview

This project investigates the relationship between everyday lifestyle habits and mental health outcomes — specifically **mood score** and **stress level** — using a dataset of 2,000 individuals.

By analyzing variables such as sleep hours, screen time, exercise minutes, fatigue level, and diet quality, we uncover which daily habits have the strongest impact on mental wellbeing.

---

## ❓ Research Question

> Do daily routine variables (sleep, exercise, diet, and digital habits) significantly influence an individual's mood and stress levels?

---

## 💡 Hypotheses

| # | Hypothesis | Test | Result |
|---|---|---|---|
| H1 | People who exercise ≥ 30 min/day have significantly higher mood scores | Pearson + T-test | ✅ Supported |
| H2 | People with screen time > 6 hrs/day have significantly lower mood scores | Pearson + T-test | ✅ Supported |
| H3 | Diet quality significantly affects mood score | One-Way ANOVA | ❌ Not Supported |


---

## 📂 Repository Structure

```
📁 repo/
├── 📓 mental_health_analysis.ipynb     ← Main Python notebook
├── 📊 mental_health_vs_daily_routine.csv  ← Dataset (2,000 records)
├── 📄 Report.docx                      ← Full written report
├── 🖼️  Poster.pdf                       ← Project poster
├── 📽️  Demo Video & PowerPoint          ← https://drive.google.com/drive/folders/1fTi_9Pf6d5dxBzv-rNLRttGry6K6vxi-?usp=drive_link
├── 📝 Contribution_Sheet                ← Team contributions
└── 📖 README.md                        ← You are here
```
```

---

## 📊 Dataset

- **Source:** Kaggle — Mental Health vs Daily Routine Dataset
- **Size:** 2,000 records × 12 features
- **Missing values:** None
- **Duplicates:** None

| Feature | Type | Description |
|---|---|---|
| `sleep_hours` | Numeric | Hours of sleep per night |
| `exercise_minutes` | Numeric | Minutes of exercise per day |
| `screen_time` | Numeric | Daily screen time in hours |
| `fatigue_level` | Numeric | Self-reported fatigue score |
| `social_hours` | Numeric | Hours spent socializing |
| `coffee_cups` | Integer | Coffee cups per day |
| `daily_pending_tasks` | Integer | Unfinished tasks per day |
| `interruptions` | Integer | Daily interruptions |
| `diet_quality` | Categorical | poor / average / good |
| `weather` | Categorical | sunny / cloudy / rainy / snowy |
| `mood_score` | Numeric | Mental wellbeing score (target) |
| `stress_level` | Numeric | Stress level score (target) |

---

## 🔬 Methodology

1. **Data Loading & Inspection** — shape, dtypes, first rows
2. **Data Cleaning** — duplicates, missing values, outlier detection (Z-score)
3. **Exploratory Data Analysis (EDA)**
   - Categorical distributions (diet quality, weather)
   - Numeric distributions (histograms for all 7 variables)
   - Correlation heatmap
   - Scatter plots (sleep, exercise, screen time vs mood & stress)
   - Box plots (diet quality, sleep categories)
   - Pareto analysis (top drivers of stress & mood)
4. **Hypothesis Testing** — Pearson Correlation, T-tests, One-Way ANOVA
5. **Conclusions**

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numeric-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-8CAAE6?logo=scipy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

---

## 📈 Key Findings

- 🏋️ **Exercise** is the strongest positive predictor of mood **(r = 0.70)**
- 📱 **Screen time** has the strongest negative effect on mood **(r = −0.29)**
- 😴 **Sleep** positively affects mood **(r = 0.16)** and reduces stress **(r = −0.30)**
- 🥗 **Diet quality** showed no statistically significant effect on mood **(p = 0.3949)**
- 📋 **Daily pending tasks** is the single largest driver of stress **(r = 0.80)**

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-repo-name/mental-health-analysis.git
```

2. Open the notebook in Google Colab or Jupyter:
```bash
jupyter notebook mental_health_analysis.ipynb
```

3. Upload the dataset when prompted:
```
mental_health_vs_daily_routine.csv
```

4. Run all cells ▶️

---

## 👥 Team Members & Contributions

| Name | Tasks |
|---|---|
| Jana Islam | Notebook, Report, Poster |
| Rania ALsaeed | Report, Proposal, Poster |
| Eyad Osama | PowerPoint, Poster, Demo Video |
| Karim Marwan | Notebook, Demo Video, Poster |

---

## 📧 Course Information

- **Course:** C-DE211 — Data Analysis
- **Institution:** Egypt University of Informatics
- **Semester:** Spring 2026
- **Supervisors:** nadine.elsaeed@eui.edu.eg | emad.emad@eui.edu.eg
