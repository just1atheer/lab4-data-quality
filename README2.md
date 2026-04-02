# Lab 4 – Data Quality & Preprocessing

##  Description
This notebook focuses on data preprocessing and improving data quality using the Insurance dataset. It includes data exploration, cleaning, normalization, and dimensionality reduction.

##  Steps Performed

### 1. Data Exploration
- Loaded the dataset using pandas
- Checked dataset structure using info() and describe()
- Identified missing values

### 2. Data Cleaning
- Handled missing values using mean
- Removed duplicate records

### 3. Outliers Detection
- Used IQR method to detect outliers

### 4. Normalization
- Applied Min-Max Scaling
- Applied Z-score Standardization

### 5. Correlation Analysis
- Used correlation matrix to analyze relationships

### 6. PCA (Principal Component Analysis)
- Reduced dimensionality to 2 components
- Transformed the dataset for easier analysis

##  Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

##  Files
- `Untitled2_fixed_executed.ipynb`
- `insurance.csv`

##  Conclusion
The dataset was successfully cleaned and transformed. PCA helped reduce dimensionality while preserving important information, making the dataset easier to analyze.
