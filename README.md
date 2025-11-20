# 🛍️ New Year Sales Analysis

This repository contains a small end-to-end **data analysis project** built using **Python** and **Jupyter Notebook**.  
The goal is to explore **New Year sale transactions**, clean the raw data, and derive useful business insights such as:

- Which products performed best during the New Year sale?
- How did sales vary across different categories, genders, and age groups?
- What is the overall revenue trend during the sale period?

---

## 📂 Project Structure

- `New Year Sales Data.xlsx`  
  Raw sales dataset containing transaction-level records.

- `NewYearSales_Cleaned.xlsx`  
  Cleaned and preprocessed dataset after handling missing values, fixing data types, and removing inconsistencies.

- `Newyeardataanalysis.ipynb`  
  Main Jupyter Notebook with the complete analysis workflow (data loading → cleaning → EDA → visualization).

---

## 🧰 Tech Stack & Libraries

The analysis is done in **Python** using a Jupyter Notebook.  
Common libraries used (install them if you don’t already have them):

- `pandas` – data loading, cleaning, transformation
- `numpy` – numerical operations
- `matplotlib` / `seaborn` – data visualization and plots
- `openpyxl` or `xlrd` – for reading Excel files (depending on your environment)
- `jupyter` – to run the notebook

You can install them via:

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```
🚀 How to Run the Project Locally


Clone the repository
```
git clone https://github.com/pawarprachi298/NewYearSalesAnalysis.git
cd NewYearSalesAnalysis
```


Create and activate a virtual environment (optional but recommended)
```
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```



Install dependencies
```
pip install -r requirements.txt
```


If requirements.txt is not present, install the libraries listed in the section above manually.



Launch Jupyter Notebook
jupyter notebook



Open the analysis notebook
In the Jupyter interface, open:
Newyeardataanalysis.ipynb

Run all cells in order to reproduce the full analysis.



🔍 Analysis Overview
In the notebook, you will typically find steps like:


# Data Loading


Importing the raw Excel file (New Year Sales Data.xlsx) into pandas.


Inspecting the columns, data types, and basic statistics.




# Data Cleaning & Preprocessing


Handling missing or null values.


Removing duplicates or invalid entries.


Converting columns (dates, numeric fields) to proper data types.


Saving a cleaned version as NewYearSales_Cleaned.xlsx.




# Exploratory Data Analysis (EDA)


Descriptive statistics (mean, median, counts, etc.).


Grouping and aggregating sales by:


Product / item


Category


Gender


Age group


Other available dimensions in the dataset






# Visualizations


Bar charts of top-selling products or categories.


Revenue comparison by gender / age group.


Any other interesting patterns observed during the New Year sale.




# Insights & Conclusions


Summary of key findings from the EDA.


Possible recommendations (for marketing, stocking inventory, targeting customers, etc.).





# 💡 Possible Extensions
If you want to extend this project, you could:


Build a dashboard using Streamlit or Power BI.


Add time-series analysis for daily/weekly sales trends.


Create customer segments and analyze each segment’s behavior.


Predict future sales using simple ML models (e.g., regression).



📜 License
This project is intended for learning and practice purposes.
You may use or modify the notebook and data for your own educational projects.

🙋‍♀️ Author
GitHub: @pawarprachi298
If you find this useful or learned something from it, feel free to ⭐ the repo!
