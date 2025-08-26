## 📊 Dataset
- Customer demographics (age, income, tenure)  
- Credit history (credit score, utilization, debt-to-income ratio)  
- Payment behavior (missed payments, repayment history)  
- Target: **Delinquent (Yes/No)**

## 🔎 Exploratory Data Analysis (EDA)
Key findings from the dataset:
- High **credit utilization (>70%)** strongly linked to delinquency.  
- Even **1–2 missed payments** is an early warning signal.  
- **Low credit score (300–600)** and **short account tenure (<2 years)** increase risk.  
- **Debt-to-income ratio >40%** is another strong risk factor.  
- Dataset required handling of missing values and anomaly checks

  ## 🤖 Model Development
- Algorithm: **Logistic Regression** (chosen for simplicity & explainability)  
- Achieved performance:  
  - **Accuracy:** 86%  
  - **Precision:** 0.84  
  - **Recall:** 0.79  
  - **F1 Score:** 0.81  
  - **AUC:** 0.90

### Top Predictive Features
1. Age (older customers less likely to default)  
2. Credit Score (higher → lower risk)  
3. Account Tenure (longer → safer)  
4. Missed Payments (increases risk significantly)  
5. Debt-to-Income Ratio (higher → higher risk)  

## 💡 Business Insights
- High-risk customers often have **low credit score, short tenure, and missed payments**.  
- Proposed **High-Risk Early Action Program**:  
  - Contact within **7 days**  
  - Offer flexible repayment options  
  - Monitor outcomes weekly
 
    **Expected Benefits:**
- Reduced delinquency rates  
- Increased repayment rates  
- Cost savings through automation  
- Improved fairness and transparency in collections

  ## 🛡 Responsible AI Practices
- **Fairness:** Monitor across age, gender, and income groups.  
- **Transparency:** Logistic regression ensures explainability.  
- **Compliance:** Align with RBI/industry rules, ensure data privacy.  
- **Human-in-the-loop:** Sensitive actions (legal escalation, restructuring) need human oversight

  ## 📈 Tools & Technologies
- **Python** (Pandas, scikit-learn)  
- **MS Word & PowerPoint** (Reports & Presentation)  
- **Excel / CSV** (Data Handling)  
- **GitHub** (Project Hosting & Documentation)  

## 🎯 Outcomes
✔ Strong predictive accuracy (**AUC 0.90**)  
✔ Business-ready strategy for early delinquency prevention  
✔ Fair, transparent, and explainable AI pipeline  
✔ Actionable recommendations for financial collections  

## 👩‍💻 Author
Mahek Jariwala – Aspiring Data Analyst  
📌 Connect with me on [LinkedIn] https://www.linkedin.com/in/mahek-jariwala-7a6586287/  

