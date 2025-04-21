 Task 1: Data Cleaning and Preprocessing
 Objective
Clean and prepare a raw dataset (`car_prices.csv`) by handling missing values, fixing formats, and ensuring consistency for further analysis or modeling.

 Tools Used
- Python (Pandas)
- Google Colab

 Steps Performed
1. **Handled Missing Values**
   - Filled categorical fields like `make`, `model`, `trim` with `'unknown'`.
   - Filled numerical fields like `condition`, `odometer`, `mmr`, and `sellingprice` with median values.
   - Converted `saledate` to datetime and filled missing dates using forward fill.

2. **Removed Duplicate Records**
   - Used `.drop_duplicates()` to ensure no redundant rows.

3. **Standardized Text Fields**
   - Converted fields like `make`, `model`, and `transmission` to lowercase and removed spaces.

4. **Renamed Columns**
   - All column names were converted to lowercase with underscores for consistency.

5. **Verified and Fixed Data Types**
   - Ensured that `saledate` is in datetime format.
   - Checked types for all other columns.
   - 
 Files Included
- `car_prices.csv`: Original dataset
- `car_prices_cleaned.csv`: Cleaned version
- `data_cleaning.ipynb`: Python notebook with the entire code


 Outcome
A clean and analysis-ready version of the `car_prices` dataset saved as `car_prices_cleaned.csv`.


