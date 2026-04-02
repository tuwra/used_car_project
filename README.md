# Used Cars Data Analysis Pipeline 🚗📊
**Student Capstone Project | ML Foundations Bootcamp**

## 📝 Project Overview
In this project, I built a data analysis pipeline for used cars. I moved from raw, messy data to a clean dataset, created new features, and built a visual dashboard to find the best car deals.

---

## 📂 Project Structure
- **`01_cleaning.ipynb`**: Loading and cleaning the data (Phase 1).
- **`02_features.ipynb`**: Creating new features and scaling data (Phase 2).
- **`03_eda.ipynb`**: Visualizing data and building the **Bonus Dashboard** (Phase 3).
- **`04_math.ipynb`**: Manual math calculations using NumPy (Phase 4).
- **`data/`**: Folder for raw and cleaned CSV files.
- **`report.pdf`**: Final 2-page written report.
- **`requirements.txt`**: List of Python libraries used.

---

## 🚀 Pipeline Phases

### Phase 1: Cleaning
- Removed missing values and duplicates.
- Fixed data types (Year to **int**, Odometer to **float**).
- Removed outliers (prices < $500 and above the 99th percentile).
- **Result:** Clean dataset with **128,752** rows.

### Phase 2: Feature Engineering
- Created **Car Age** and **Mileage per Year**.
- Applied **Ordinal Encoding** to the car condition.
- Applied **One-Hot Encoding** to fuel and transmission types.
- Used **StandardScaler** to normalize mileage and age.
- Applied **Log Transformation** to the price for better distribution.

### Phase 3: Visual Analysis 
- Created a **4-Chart Dashboard** in one figure.
- Analyzed price distribution, mileage impact, and brand performance.
- Used a **Correlation Heatmap** to find the strongest price predictors.

### Phase 4: Math Basics
- Calculated Mean and Standard Deviation **manually** using NumPy.
- Calculated **Cosine Similarity** between high-value and low-value cars.
- Estimated the **Probability** of finding expensive cars (> $50,000).

---

## 📈 Key Findings
- **Age is King:** Car age is the most significant factor affecting price.
- **Condition vs. Mileage:** A car in "Excellent" condition can hold more value than a newer car with lower mileage.
- **Brand Value:** Manufacturers like Toyota and Ford show stronger price retention over time.

---

## - **Kaggle Link:** [Used Cars Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)

---

## 👤 Author
- **Raeed Alotaibi** - https://github.com/tuwra

---
*This project was completed as part of the ML Foundations Bootcamp in Tuwaiq Academy.*
