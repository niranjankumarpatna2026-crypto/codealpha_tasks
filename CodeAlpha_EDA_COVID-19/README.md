# 🦠 COVID-19 Clinical Trials - Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12%2B-yellow)
![License](https://img.shields.io/badge/License-MIT-red)

## 📋 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a dataset of COVID-19 clinical trials obtained from ClinicalTrials.gov. The analysis aims to understand the characteristics, distribution, and global trends of clinical research conducted during the pandemic.

## 📊 Dataset Information

The dataset consists of **two files** downloaded from Kaggle:

| File | Description | Records | Columns |
|------|-------------|---------|---------|
| `COVID clinical trials.csv` | Main dataset with trial details | 5,783 | 27 |
| `COVID clinical trials metadata.xlsx` | Metadata explaining column descriptions | - | - |

### 📁 Dataset Files

1. **`COVID clinical trials.csv`** - Main data file containing information about 5,783 clinical trials including:
   - NCT Number, Title, Status, Phases
   - Enrollment numbers
   - Locations and Countries
   - Start and Completion Dates
   - Study Type and Design

2. **`COVID clinical trials metadata.xlsx`** - Metadata file explaining each column in detail, including:
   - Column names and descriptions
   - Data types
   - Value explanations

**Dataset Source:** [COVID-19 Clinical Trials on Kaggle](https://www.kaggle.com/datasets/nailasrivastava/covid-19-clinical-trials-data)

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python 3.8+** | Primary programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **openpyxl** | Reading Excel metadata file |

## 📈 Key Insights

| Insight | Finding |
|---------|---------|
| **Total Trials** | 5,783 trials analyzed |
| **Status Distribution** | 2,805 trials (48.5%) were in "Recruiting" status |
| **Most Common Phase** | Phase 2 trials were most frequent among interventional studies |
| **Top Country** | United States leads with 1,267 trials |
| **Median Enrollment** | 170 participants per trial |
| **Peak Period** | Sharp increase in trial initiations during 2020 |
| **Study Type** | Interventional studies outnumber observational studies |


## 🚀 Installation & Setup

### Prerequisites

Ensure Python 3.8 or higher is installed on your system.

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/COVID19-Clinical-Trials-EDA.git
cd COVID19-Clinical-Trials-EDA
