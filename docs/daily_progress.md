## 🗓 Retail Sales Analytics Dashboard – Daily Progress Log



## \*\*Day 1 – Project Setup\*\*

\- Created project folder structure (`data`, `scripts`, `notebooks`, `dashboard`, `report`, `docs`)

\- Initialized local Git repository and linked to GitHub

\- Added and pushed README.md with project overview



✅ Deliverables:

\- Project folder structure

\- README.md



---



## \*\*Day 2 – Data Familiarization\*\*

\- Added raw dataset (SuperMarket Analysis.xlsx) to `/data/raw/`

\- Explored dataset structure in Excel and Jupyter

\- Verified columns such as Invoice ID, City, Product Line, Payment, Date, Time



✅ Deliverables:

\- `/data/raw/SuperMarket Analysis.xlsx`



---



## \*\*Day 3 – Business Understanding\*\*

\- Defined 8 core business questions for analysis

\- Created and uploaded `/docs/business\_questions.txt` to GitHub



✅ Deliverables:

\- `/docs/business\_questions.txt`



---



## \*\*Day 4 – Data Understanding\*\*

\- Opened dataset and reviewed columns

\- Created `/docs/data\_dictionary.xlsx` explaining each column’s meaning and type

\- Uploaded it to GitHub



✅ Deliverables:

\- `/docs/data\_dictionary.xlsx`



---



## \*\*Day 5 – Data Cleaning \& Preparation\*\*

\- Loaded dataset in Jupyter Notebook using Pandas

\- Checked for null values, duplicates, and incorrect data types

\- Fixed Date and Time formats and cleaned data

\- Saved cleaned dataset to `/data/cleaned/supermarket\_sales\_cleaned.xlsx`

\- Updated daily progress log and pushed to GitHub



✅ Deliverables:

\- `/data/cleaned/supermarket\_sales\_cleaned.xlsx`

\- Updated `/docs/daily\_progress.md`



---

## 🗓️ Day 6 – Exploratory Data Analysis (EDA)

### 📊 Tasks Completed
- Loaded cleaned dataset successfully from `/data/cleaned/supermarket_sales_cleaned.xlsx`
- Verified column types and checked for duplicates and missing values
- Created exploratory visualizations:
  - Total Sales by City (`sales_by_city.png`)
  - Sales by Product Line (`sales_by_product_line.png`)
  - Monthly Sales Trend (`monthly_trend.png`)
  - Payment Method Distribution (`payment_share.png`)
  - Correlation Heatmap (`corr_matrix.png`)
- Generated summary tables:
  - `data/processed/sales_by_city.csv`
  - `data/processed/monthly_sales.csv`
- Wrote insights summary → `docs/eda_summary_day6.md`

### 📈 Key Findings
- **Total Sales:** ₹322,966.75  
- **Transactions:** 1,000  
- **Average Sale Value:** ₹322.97  
- **Top City:** Yangon  
- **Top Product Line:** Fashion Accessories  
- **Most Used Payment:** E-wallet  

### 📁 Deliverables
- `/notebooks/eda_day6.ipynb`
- `/data/processed/*.csv`
- `/notebooks/figures/*.png`
- `/docs/eda_summary_day6.md`

---



