# 🏦 Loan Defaulter Risk Analysis (EDA with Python)

### 📘 Overview  
Exploratory Data Analysis (EDA) on loan applicant data to identify **risk factors** and **reduce loan defaults**.  
The goal is to understand **customer behavior**, **credit patterns**, and **default risk** using data-driven insights.

---

### 🎯 Objectives  
- Apply EDA in a real-world financial context  
- Analyze customer demographics, income, and loan history  
- Identify safe borrower profiles and high-risk patterns  
- Support better credit and lending decisions  

---

### 🗂️ Dataset  

📍 Source: [Kaggle - Loan Defaulter Dataset](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter)

---

### 🔧 Data Cleaning & Feature Engineering  
- Dropped columns with **>40% missing values** & low correlation with `TARGET`  
- Handled missing data using **mode**, **mean**, or **proportional filling**  
- Applied **quantile-based binning** for continuous variables  
- Created merged dataset to link current and previous loan history  

---

### 📊 Key Insights  
- **Females**, **married**, **educated**, **homeowners** show lowest default rates  
- **Low-skill laborers** and **drivers** are high-risk segments  
- **Transport Type 3** organizations show highest default tendency  
- **80–90%** of previously refused/canceled applicants are now repayers  
- Loans with **credit ≤ 1M** and **annuity ≈ 50K** are safer  

---

### 💡 Recommendations  
✅ Target borrowers with:  
- Income < 1M  
- Stable occupation (Accountants, Managers, Core Staff)  
- Home ownership & education  
- Small families (≤5 children)  

🚫 Avoid:  
- Low-skill laborers, drivers  
- Transport Type 3 organizations  
- Previously refused loan profiles  

---

### 🧰 Tools & Libraries  
`Python` | `Pandas` | `NumPy` | `Matplotlib` | `Seaborn`

---

### 📈 Conclusion  
The analysis helps financial institutions **minimize loan default risks** by identifying safer borrower segments and optimizing loan strategies through **data-driven insights**.

📄 Detailed Report: *Included in PDF format*  



