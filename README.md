# A/B Testing Analysis – Promotion Campaign Impact on Average Order Value
### 📌 Business Problem

A new promotional campaign was launched to increase Average Order Value (AOV).
The objective of this analysis is to determine whether the promotion significantly increases customer spending.

### 🎯 Objective

Evaluate whether the treatment group (new promotion) has a higher Average Order Value than the control group using statistical hypothesis testing.

### 🧠 Hypothesis

Let:

μ₁ = Mean AOV (Control Group)

μ₂ = Mean AOV (Treatment Group)

Null Hypothesis (H₀):
The promotion does not increase AOV.
μ₂ ≤ μ₁

Alternative Hypothesis (H₁):
The promotion increases AOV.
μ₂ > μ₁

Significance Level (α): 0.05
Confidence Level: 95%

### 🛠 Tools & Technologies

Python

Pandas (Data manipulation)

SciPy (Statistical testing)

NumPy

Matplotlib / Seaborn (Visualization)

Excel (Dashboard & Executive Reporting)

#### 📂 Dataset

Source: Kaggle A/B Testing Dataset

Dataset contains:

user_id

group (control / treatment)

converted

revenue (simulated for AOV testing)

### 🔎 Methodology

Data Cleaning

Removed duplicates

Validated group consistency

Ensured correct data types

Exploratory Data Analysis

Calculated Average Order Value per group

Visualized AOV distribution

Statistical Testing

Independent One-Tailed T-Test

Compared treatment vs control

Evaluated p-value against alpha (0.05)

Business Impact Estimation

Calculated % lift

Estimated monthly revenue impact

### 📊 Results
Metric	Value
Control AOV	144.58
Treatment AOV	142.97
Lift	-1.1%
Significance Level	0.05
Interpretation

The treatment group showed a slightly lower Average Order Value compared to the control group.

Statistical testing was conducted to determine whether this difference is significant.

### 💼 Business Recommendation

If statistically significant:

Do not roll out promotion

Investigate pricing strategy

Analyze customer segmentation impact

If not statistically significant:

No strong evidence of impact

Further testing recommended

### 📈 Deliverables

Jupyter Notebook (Full Statistical Pipeline)

Excel Dashboard (Executive Summary)

Business Impact Analysis

Visualization Charts

### 🚀 Key Skills Demonstrated

Hypothesis Testing

A/B Test Design

Statistical Significance Interpretation

Business Impact Estimation

Data Visualization

Executive Reporting

### 📌 Project Structure
'''text 
/data
/notebooks
/excel_dashboard
/README.md
🔥 Optional Upgrade (If You Want It Stronger)
'''


### “What I Learned”

Not all experiments produce positive lift

Statistical significance must guide business decisions

Small numerical differences may not be meaningful

Data-driven decision making prevents revenue loss
