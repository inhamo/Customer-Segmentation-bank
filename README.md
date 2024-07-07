# Customer Segmentation Analysis for Global Bank

This repository contains the code and analysis for the customer segmentation project conducted for Global Bank. The goal of this project was to segment the bank's customers based on their demographic, transactional, and geographical data to derive actionable business insights.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Libraries Used](#libraries-used)
- [Skills Obtained](#skills-obtained)
- [Analysis Workflow](#analysis-workflow)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to identify distinct customer segments within Global Bank's customer base to enhance marketing strategies, product offerings, and customer engagement. The analysis involved data cleaning, preprocessing, exploratory data analysis, and clustering.

## Data

The dataset used for this project includes the following features:
- **https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation**
- 
- **CustGender**: Gender of the customer
- **CustAccountBalance**: Account balance of the customer
- **TransactionAmount**: Amount of each transaction
- **Age**: Age of the customer
- **BalTransRatio**: Ratio of balance to transaction amount
- **TransactionMonth**: Month of the transaction
- **Geographical Locations**: Cities where the transactions occurred

## Libraries Used

The following Python libraries were used in this project:

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Scikit-learn**: Machine learning algorithms for clustering and preprocessing
- **Jupyter Notebook**: Interactive computing environment

## Skills Obtained

Through this project, the following skills were developed:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data visualization
- Clustering algorithms (e.g., K-means)
- Customer segmentation analysis
- Deriving business insights from data
- Reporting and documentation

## Analysis Workflow

1. **Data Cleaning**: Addressed issues such as unreasonable date of birth values, missing data, and removed insignificant locations.
2. **Exploratory Data Analysis**: Analyzed demographic, geographical, and transactional patterns.
3. **Clustering**: Applied clustering algorithms to identify distinct customer segments.
4. **Visualization**: Created visualizations to illustrate key findings.
5. **Reporting**: Summarized insights and recommendations in a comprehensive report.

## Key Findings

- Significant gender imbalance with 72% male and 28% female customers.
- Age group 21 showed the highest mean transaction/balance ratio.
- Major customer concentrations in Mumbai, Bangalore, and New Delhi.
- Seasonal spikes in transactions observed in August and September.
- Three distinct customer clusters identified based on gender, account balance, transaction frequency, and age.

## Recommendations

1. **Enhanced Marketing Strategies**: Targeted campaigns and gender-specific promotions.
2. **Product Development**: Custom products for different age groups and locations.
3. **Customer Engagement**: Personalized communication and financial advice.
4. **Data-Driven Decision Making**: Regular analysis and CRM integration.
5. **Visualization and Reporting**: Interactive dashboards and regular reporting.

## Usage

To reproduce the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/global-bank-customer-segmentation.git
   cd global-bank-customer-segmentation
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks in the `notebooks` directory to see the analysis steps and results.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For any questions or support, please contact [Innocent Nhamo](mailto:itnhamo@gmail.com).

---

**Note**: This repository is a part of the customer segmentation analysis project for Global Bank and contains confidential information. Please handle the data responsibly and adhere to the bank's data privacy policies.
