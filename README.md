# 🧪 Exploratory Data Analysis on Titanic Dataset

This repository contains a complete Exploratory Data Analysis (EDA) performed on the famous Titanic dataset. The goal is to understand the dataset using summary statistics, visualizations, correlation analysis, and pattern recognition.

---

## 📌 Objective

- Analyze the Titanic dataset to understand feature behavior and relationships.
- Identify trends, outliers, and possible data issues.
- Use visualization to support basic feature-level insights.

---

## 📊 EDA Steps Covered

### ✅ Step 1: Generate Summary Statistics
- Used `.describe()` to get count, mean, std, min, max, and percentiles.
- Calculated individual `mean`, `median`, and `std` for numeric columns.

### ✅ Step 2: Visualize Numeric Features
- Plotted **histograms** to see distribution of numerical features.
- Used **boxplots** to detect outliers and observe spread.

### ✅ Step 3: Analyze Feature Relationships
- Plotted a **correlation matrix** using a heatmap.
- Created a **pairplot** for key features like `Age`, `Fare`, `Pclass`, `Survived`.

### ✅ Step 4: Identify Patterns, Trends, or Anomalies
- Examined **Age distribution vs Survival** to understand impact.
- Boxplot of **Fare vs Survival** to detect outliers and high-value trends.
- Detected anomalies in `Fare` with extreme values.

### ✅ Step 5: Make Basic Feature-Level Inferences from Visuals
- Found **women had higher survival rates** using a barplot (`Sex` vs `Survived`).
- First-class passengers had **better survival chances** (`Pclass` vs `Survived`).
- Older passengers had a lower survival rate overall.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (optional)

---

## 📂 Dataset

- **Titanic dataset**
- You can download it from [Kaggle Titanic](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Or upload your `titanic.csv` file when running the notebook in Colab

---

## ▶️ How to Run

1. Clone the repository or upload the notebook to Google Colab.
2. Upload the `titanic.csv` file when prompted.
3. Run each cell in order to perform the EDA.

---

## 📈 Example Insights

- **Gender Matters**: Females had a much higher survival rate.
- **Class Impact**: Higher class = higher survival chance.
- **Age Influence**: Young children had better survival odds than the elderly.
- **Fare Outliers**: Some passengers paid exceptionally high fares.

---

---

## 📝 Submission

This project is submitted as **Task 2** of the AI/ML Internship and hosted on GitHub as part of the evaluation process.

---
## 👤 Submitted by

- **Kannati Naveena**  
- GitHub: [kannatinaveena](https://github.com/kannatinaveena)
