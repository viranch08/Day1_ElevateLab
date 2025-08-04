# Data Cleaning Task – Customer Personality Analysis (Excel)

## 📌 Objective
The goal of this project was to clean and prepare a raw dataset (`customer personality analysis.csv`) using **Microsoft Excel** by handling nulls, fixing inconsistent formats, and preparing it for analysis.

## 🛠️ Tools Used
- Microsoft Excel

## 📂 Dataset
- **Name**: Customer Personality Analysis  
- **Source**: Kaggle  
- **Raw File**: `customer personality analysis.csv`  
- **Cleaned File**: `customer personality_cleaned.xlsx`

## 🧹 Cleaning Steps Performed in Excel

1. **Handled Missing Values:**
   - Replaced blank `Income` values with the average income (₹52,247).

2. **Removed Duplicates:**
   - Used Excel’s “Remove Duplicates” feature to remove identical rows based on all columns.

3. **Standardized Column Headers:**
   - Renamed columns to be lowercase, with underscores instead of spaces (e.g., `Year_Birth` → `year_birth`).

4. **Formatted Dates:**
   - Converted `Dt_Customer` to a consistent format (`DD-MM-YYYY`).

5. **Verified Data Types:**
   - Ensured `Year_Birth`, `Income`, etc., are stored as numerical columns.
   - Checked dates and text fields for formatting issues.

## ✅ Final Output
- `customer personality_cleaned.xlsx`: Cleaned dataset ready for analysis.
- Removed rows with duplicate data.
- Filled missing income values with mean.

## 📎 Notes
- This dataset is now ready for use in Power BI, Tableau, or further Python analysis.
- Data integrity was preserved while applying Excel transformations.

