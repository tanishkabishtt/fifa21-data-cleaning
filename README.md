# FIFA 21 Player Data — Cleaned & Visualized

This project demonstrates a complete data cleaning and visualization workflow using Python and Excel. The dataset was sourced from Kaggle and contained messy, unstructured information about FIFA 21 players. I cleaned the data, generated summary insights, and added visual charts to make it client-ready.

## 📦 Files Included

- `fifa21_raw_data.csv` — original messy dataset from Kaggle  
- `fifa21_cleaned_with_summary_and_charts.xlsx` — cleaned and formatted Excel file with:
  - Summary sheet (average age, height, weight, potential, overall)
  - Bar chart of top 10 player positions
  - Pie chart of top 10 nationalities  
- `fifa21-data-cleaning.ipynb` — Google Colab notebook with full cleaning and visualization code

## ✅ Cleaning Tasks Performed

- Renamed misencoded columns (e.g., `'ã†ova'` → `'overall'`)
- Removed duplicates and handled missing values
- Converted data types for numeric analysis
- Verified realistic ranges for age, height, weight, potential, and overall
- Created summary statistics and visual charts using `openpyxl`

## 📊 Tools Used

- Python (pandas, openpyxl)
- Google Colab
- Excel (for final formatting and chart rendering)

## 💼 Use Case

This cleaned dataset is ready for:
- Dashboards and reporting
- Client analysis and insights
- Freelance portfolio samples

## 🔗 Source

Original dataset: [FIFA 21 Messy Raw Dataset on Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring)

---

