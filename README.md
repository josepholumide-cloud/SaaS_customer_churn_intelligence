
# SaaS Customer Churn Intelligence

**Author:** Joseph Ogunselu  
**Email:** ogunselujoseph992@gmail.com

## 📌 Project Overview

This project analyzes SaaS customer data to understand customer churn patterns and identify factors associated with customers leaving a subscription-based service. Using Python, Pandas, Matplotlib, and Seaborn, the analysis explores churn across subscription plans, industries, payment statuses, countries, and customer engagement metrics.

## 🎯 Objectives

- Analyze customer churn patterns in a SaaS business.
- Identify subscription plans with the highest number of churned customers.
- Examine churn across industries, countries, and payment statuses.
- Compare customer engagement indicators, including active seats, feature adoption, and support tickets.
- Generate insights that can help inform customer retention strategies.

## 🛠️ Tools and Technologies

- **Python** — data analysis
- **Jupyter Notebook** — interactive analysis
- **Pandas** — data cleaning and manipulation
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization

## 📂 Dataset

The project uses a synthetic SaaS customer dataset containing **50,000 records**.

The dataset includes information such as:

- Customer and company details
- Signup and last-active dates
- Subscription plan tier
- Industry and country
- Payment status
- Active seats
- Feature adoption rate
- Support tickets
- Customer churn status

> **Note:** The dataset is synthetic. The original notebook references a local CSV file, so update the file path to match your environment before running the analysis. Do not upload private or restricted data to GitHub.

## 🔍 Analysis Process

1. Imported the dataset using Pandas.
2. Cleaned column names and checked for missing values and duplicate records.
3. Converted date columns to datetime format.
4. Filtered records for churned customers.
5. Cleaned the feature adoption rate field.
6. Analyzed churn by subscription plan, industry, country, payment status, and account manager.
7. Examined last-active dates and customer engagement indicators.
8. Summarized the findings to identify potential retention opportunities.

## 📊 Key Findings

Based on the notebook analysis:

- **Total records:** 50,000
- **Churned records:** 916
- **Observed churn rate:** 1.83%
- **Starter plan:** 685 churned customers, representing approximately 74.8% of the churned records.
- **Average active seats:** Churned customers had approximately 24.8 active seats, compared with 50.8 across the full dataset.
- **Feature adoption:** Churned customers had an average feature adoption rate of approximately 52%.
- **Support tickets:** Churned customers averaged approximately 5 support tickets in the last 30 days, compared with 3.35 across the full dataset.
- **Payment status:** Among churned records, 513 had Active payment status, 294 had Failed payment status, and 109 had Pending payment status.

These findings are descriptive. They show patterns in the dataset but do not establish that any particular factor caused churn.

## 💡 Potential Business Recommendations

- Investigate why the Starter plan accounts for the largest number of churned customers.
- Monitor customer engagement and feature adoption to identify accounts that may need support.
- Review support-ticket trends to identify recurring customer problems.
- Examine failed and pending payments as potential areas for billing follow-up.
- Conduct further analysis before implementing retention strategies.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Replace the placeholder URL with your actual GitHub repository URL.

### 2. Install dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Prepare the dataset

Place the CSV dataset in the appropriate directory and update the file path in the notebook.

### 4. Run the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells in order.

## 📁 Suggested Repository Structure

```text
saas-customer-churn-intelligence/
├── README.md
├── python6(1).ipynb
├── data/
│   └── README.md
└── requirements.txt
```

Keep the actual dataset out of the repository if it is large, private, or restricted. The `data/README.md` file can explain how to obtain or prepare it.

## 🔮 Future Improvements

- Build a predictive churn model using machine learning.
- Identify customers at high risk of churn.
- Evaluate churn rates across customer segments.
- Develop an interactive dashboard.
- Investigate relationships between payment issues, engagement, support activity, and churn.
- Validate findings using additional data and statistical testing.

## 👤 Author

**Joseph Ogunselu**  
Email: [ogunselujoseph992@gmail.com](mailto:ogunselujoseph992@gmail.com)

---

*This project demonstrates exploratory data analysis and business insight generation using Python.*
