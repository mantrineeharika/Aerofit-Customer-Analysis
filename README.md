# Aerofit-Customer-Analysis
Analysis of Aerofit treadmill customer data to understand purchasing behavior, identify customer segments, and derive insights for better marketing and product strategies.
# 🏋️‍♂️ Aerofit Treadmill Customer Analysis  
Descriptive Statistics & Probability | Data Analysis Project

## 📌 Project Overview
Aerofit is a leading fitness equipment brand offering treadmills, exercise bikes, and gym machines.  
This project analyzes customer demographics and usage patterns to help Aerofit understand **which type of customers prefer which treadmill model** (KP281, KP481, KP781).

The goal is to identify:
- Customer behavior
- Factors influencing product choice
- Insights for targeted marketing and product improvement

---

## 📂 Dataset Description
The dataset contains **180 customer records** with the following attributes:

| Column | Description |
|--------|-------------|
| Product | Treadmill model purchased (KP281 / KP481 / KP781) |
| Age | Customer age |
| Gender | Male / Female |
| Education | Education level |
| MaritalStatus | Single / Partnered |
| Usage | Weekly treadmill usage (times per week) |
| Fitness | Fitness rating (1–5) |
| Income | Annual income |
| Miles | Average weekly miles walked/ran |

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas** – Data cleaning & analysis  
- **NumPy** – Numerical computation  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook / Google Colab** – Code execution  

---

## 📊 Project Work Summary

### ✔ Data Cleaning  
- Checked for missing values (none found)  
- Verified data types  
- Looked for outliers using:  
  - Boxplots  
  - IQR method  
  - Mean vs Median difference  

### ✔ Non-Graphical Analysis  
- `value_counts()` for categorical columns  
- `nunique()` for unique values  
- Summary statistics using `describe()`  

### ✔ Visual Analysis  
Performed **univariate, bivariate, and multivariate analysis**:

#### 🔹 Univariate  
- Age distribution  
- Income distribution  
- Miles walked weekly  
- Product counts  
- Gender distribution  

#### 🔹 Bivariate  
- Age vs Income  
- Income vs Miles  
- Gender vs Miles  
- Marital Status vs Usage  
- Product vs Marital Status  

#### 🔹 Correlation  
- Heatmap  
- Pairplot  

### ✔ Outlier Detection  
Applied IQR method to:  
- **Income**  
- **Miles**

### ✔ Probability Analysis  
Calculated marginal probability of product purchase:

| Product | Count | Percentage |
|---------|--------|------------|
| KP281 | 80 | 44.44% |
| KP481 | 60 | 33.33% |
| KP781 | 40 | 22.22% |

---

## 📌 Key Insights

### ⭐ Product KP281  
- Preferred by younger customers  
- Lower to mid-income group  
- Moderate usage frequency  

### ⭐ Product KP481  
- Middle-aged customers  
- Balanced fitness level  
- Average weekly miles  

### ⭐ Product KP781  
- High-income customers (₹80k–₹1 lakh+)  
- Strong fitness level  
- Highest weekly miles  
- Used by more dedicated fitness users  

### ⭐ Other Insights  
- Males purchased more treadmills than females  
- Partnered individuals bought more units than singles  
- Higher education slightly correlates with higher product category  

---

## 🏁 Conclusion
This project helps Aerofit identify:

- Which customer segments prefer which treadmill model  
- How age, income, and fitness level influence purchasing decisions  
- Better marketing strategies for different customer groups  
- Data-driven insights to improve product recommendations  

Aerofit can use these findings to tailor their sales approach and enhance customer satisfaction.

---

## 📎 Project Files
- `aerofit_treadmill.txt` – Dataset  
- `Aerofit_Project.ipynb` – Analysis Notebook  
- `Aerofit.Project.pdf` – PDF Report  

---

## 👩‍💻 Author
**Neeharika**  
Data Science Learner | SQL • Python • Analytics  
