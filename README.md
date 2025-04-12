# 💼 Bank Loan Analysis

## 🧾 Abstract  
This project presents a detailed and interactive dashboard for **bank loan analysis**, developed to assist financial institutions in evaluating and managing loan applications more effectively. The dashboards leverage machine learning and data visualization to identify risk patterns, streamline loan assessments, and enhance decision-making. Built using Python (Dash, Plotly) and visualized with tools like Power BI, this solution combines predictive analytics with interactive interfaces to improve the transparency, speed, and accuracy of loan evaluations.


## 1. 🧩 Problem Statement  
The increasing complexity of loan applications and risk factors has made traditional, manual evaluation methods inefficient. This project addresses the challenges of rising NPAs and inconsistent approval processes by introducing a data-driven dashboard for loan analysis. It aims to improve operational efficiency, mitigate risk, and support transparent decision-making using real-time loan data.


## 2. 🎯 Objectives  
- Provide **real-time insights** into customer loan data  
- Reduce financial risk by **identifying defaulter patterns**  
- Support loan officers through a **user-friendly visualization tool**  
- Improve the **efficiency and transparency** of loan approvals  
- Leverage machine learning to **predict loan approval outcomes**


## 3. 🔍 Steps Followed  
- **Data Ingestion**: Loading loan data from CSV or database sources  
- **Data Preprocessing**: Handling missing values, encoding, normalization  
- **Feature Engineering**: Creating new metrics (e.g., income-to-loan ratio)  
- **Model Training**: Applied Logistic Regression and Random Forest  
- **Visualization**: Built interactive dashboards using Dash, Plotly, and Power BI  
- **Insights & Evaluation**: Analyzed model performance (accuracy, precision, recall)


## 4. 📊 Key Insights from Dashboards  

- 38.6K total loan applications, $435.8M funded, $473.1M received  
- **Good loans**: 86.2% (33K apps), **Bad loans**: 13.8% (5K apps)  
- **Top loan purpose**: Debt consolidation  
- 60-month loans are most common; renters received the highest loan amounts  
- Credit history, income, and employment status are key predictors of loan approval


## 5. 🛠 Tech Stack  
- 	**Microsoft SQL Server:** Used for storing, managing, and querying structured financial data efficiently.
- **Power BI:** A business analytics tool used for creating interactive visual reports and dashboards.
- **Plotly, Pandas, NumPy, Matplotlib, Scikit-learn:**
    -	Plotly: Used for building interactive data visualizations.
    - Pandas & NumPy: Essential for data manipulation and numerical operations.
    -	Matplotlib: Used for basic data visualization and plotting.
    - Scikit-learn: A machine learning library used for implementing classification and predictive models.
 



## 6. ✨ Features  
- Three **interactive dashboards**:  
  - **Summary Dashboard**: Total applications, interest rates, loan status breakdown  
  - **Overview Dashboard**: Insights by purpose, experience, ownership, etc.  
  - **Detailed Report Dashboard**: Individual-level records with filters  
- Real-time predictions using trained ML models  
- Dynamic filtering for demographic and financial features  
- Intuitive layout designed for both technical and business users  
- Predictive accuracy comparison: Random Forest outperforms Logistic Regression


## 7. 📈 Results  
### 🔹 Summary Dashboard  
![Summary Dashboard](https://github.com/nadargeAnkita/Bank_Loan_Analysis/blob/main/Bank-Loan-Analysis/images/Summary.png)
- The Bank Loan Summary Dashboard highlights 38.6K loan applications with $435.8M funded and $473.1M received. The average interest rate is 12.0%, and the DTI stands at 13.3%. Good loans represent 86.2% (33K apps, $370.2M), while bad loans make up 13.8% (5K apps, $65.5M). The loan status table breaks down applications, amounts, interest rates, and DTI across categories: Charged Off, Current, and Fully Paid.
### 🔹 Overview Dashboard  
![Overview Dashboard](https://github.com/nadargeAnkita/Bank_Loan_Analysis/blob/main/Bank-Loan-Analysis/images/Overview.png)
- This Bank Loan Overview Dashboard summarizes 38.6K applications, $435.8M funded, and $473.1M received, with an average interest rate of 12% and DTI of 13.3%. Key insights show steady monthly funding growth, 60-month loans as most common, top funding from applicants with 10+ years experience, and debt consolidation as the leading loan purpose. Renters received the highest loan amounts, and applications are spread across multiple states.
### 🔹 Details Dashboard  
![Details Dashboard](https://github.com/nadargeAnkita/Bank_Loan_Analysis/blob/main/Bank-Loan-Analysis/images/Details.png)
- The Bank Loan Report – Details Dashboard offers an overview of individual loan records, covering loan purposes (e.g., car, small business, debt consolidation), ownership status (MORTGAGE, RENT, OWN), grades (A–E), and issue dates (mainly Jan 2021). Funded amounts range from $3K to $25K with interest rates between 0.06 and 0.20. Monthly instalments vary from under $130 for smaller loans to over $800 for higher loans, helping assess borrower profiles and repayment trends.





## 8. 🚀 Conclusion & Future Scope  
This project successfully demonstrates how **data science and interactive dashboards** can optimize loan evaluation processes. The system supports fast, data-driven decisions and aids in identifying default patterns, ultimately helping reduce NPAs.

**Future Enhancements**:  
- Integrate real-time data using APIs for up-to-date analysis.
- Deploy on cloud platforms to enhance accessibility and scalability.
- Implement more advanced models like XGBoost and deep learning for improved prediction accuracy.
- Add customer profiling to provide personalized loan recommendations.
- Incorporate additional financial indicators for deeper risk analysis.




## 🙌 Let's Connect  
Feel free to reach out or suggest improvements!  
🔗 [LinkedIn](https://www.linkedin.com/in/ankita-nadarge/) 

🔗 [Github](https://github.com/nadargeAnkita/Bank_Loan_Analysis.git)  
📧 ankitanadarge@email.com

