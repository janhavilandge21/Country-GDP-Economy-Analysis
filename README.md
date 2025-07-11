# 🌍 Country GDP Economy Analysis

This project focuses on exploring and analyzing global economic indicators using real-world data. The dataset contains information about countries' **Birth Rate**, **Internet Usage**, and **Income Group**. The aim is to understand patterns, relationships, and insights through data cleaning, analysis, and visualization using Python.

## 📁 Project Structure


## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset Columns

- `CountryName`: Full name of the country
- `CountryCode`: ISO code of the country
- `BirthRate`: Number of births per 1000 people
- `InternetUsers`: Percentage of internet users in the country
- `IncomeGroup`: Economic classification (High income, Low income, etc.)

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Data Cleaning
- Checked for missing values using `df.isnull()` and `df.isna()`
- Verified datatypes and column integrity with `df.info()`

### 📈 Descriptive Statistics
- Used `df.describe()` to observe mean, median, min, max, and standard deviation
- Analyzed distributions for numeric data

### 🔍 Filtering and Subsetting
- Countries with very low internet usage (`InternetUsers < 2%`)
- Countries with high birth rates (`BirthRate > 40`)
- Grouped data by `IncomeGroup`

### 📊 Visualizations
- Histogram for Internet Usage (`sns.displot`)
- Boxplot: IncomeGroup vs BirthRate
- Regression plots (Linear Relationship):
  - InternetUsers vs BirthRate
  - Colored by IncomeGroup

## 📌 Key Insights

- Countries with lower income groups tend to have higher birth rates and lower internet usage.
- Internet usage has a negative correlation with birth rate.
- IncomeGroup classification plays a vital role in understanding economic disparities.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/janhavilandge21/Country-GDP-Economy-Analysis.git

2.Install required packages:   
pip install pandas numpy matplotlib seaborn jupyter

3.Run the Jupyter notebook:
jupyter notebook Country_GDP_Economy_Analysis.ipynb

🧠 Future Work
Merge this data with GDP or population datasets for deeper analysis.

Implement interactive dashboards using Plotly or Power BI.

Use clustering to categorize countries based on multiple indicators.

🙋‍♀️ Author
Janhavi Landge

Data Science & AI Enthusiast

GitHub: @janhavilandge21


