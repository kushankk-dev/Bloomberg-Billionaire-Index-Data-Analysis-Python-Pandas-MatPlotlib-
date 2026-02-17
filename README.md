Bloomberg Billionaires Wealth Analysis
Overview-:
This project performs Exploratory Data Analysis (EDA) on a 500-record Bloomberg Billionaires dataset to examine global wealth distribution, geographic concentration, and industry-level dominance.
The analysis applies statistical measures, aggregation techniques, and correlation analysis to evaluate structural wealth inequality.
Dataset
Source: Kaggle (Bloomberg Billionaires Index)
Records: 500 billionaires
Features included:
•	Rank
•	Name
•	Total Net Worth
•	YTD Change
•	Last Change
•	Country / Region
•	Industry

Tools and Technologies
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Google Colab

Statistical Insights
•	Mean Net Worth: $20.11 BN
•	Median Net Worth: $11.0 BN
•	Skewness (Fisher–Pearson coefficient): 6.69

The large positive skewness confirms a strongly right-skewed distribution, indicating extreme wealth concentration among a small number of individuals.
Geographic Analysis
•	United States:
o	191 billionaires
o	Controls 50.8% of total billionaire wealth
•	The top three countries account for approximately 65% of total wealth.
Wealth concentration is heavily centralized within major developed economies and technology sector particularly the United States.

Industry Analysis-
•	Technology sector records the highest average net worth (37.86).
•	Innovation-driven industries demonstrate significantly higher wealth accumulation.
•	Traditional sectors such as Energy and Finance show comparatively moderate averages.

Correlation Findings
•	Weak correlation (approximately -0.03) between total net worth and short-term wealth changes reflecting independence of total wealth to short term mark to market changes.
•	Short-term financial fluctuations appear largely independent of accumulated net worth.

Techniques Applied
•	Data cleaning and preprocessing
•	Regex-based numeric extraction
•	GroupBy aggregation
•	Statistical distribution analysis
•	Skewness computation
•	Correlation matrix evaluation
•	Data visualization using Matplotlib

Files Included
•	billionaires_eda.ipynb – Exploratory data analysis notebook
•	Bloomberg Billionaires Data Analysis-Kushank.pdf– Structured analysis report
•	Dataset file
Conclusion
The analysis demonstrates significant global wealth parity, high geographic concentration of wealth, and industry-driven wealth accumulation patterns. The project highlights practical application of data cleaning, statistical computation, aggregation analysis, and visualization using Python.
