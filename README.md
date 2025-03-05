# Cafe-Sales-Data-Analysis<br>
1. Data Loading and Initial Exploration:
The notebook starts by loading the dataset using Pandas and displaying basic information like data types and missing values.
It then shows the first and last 10 rows of the dataset to give an initial overview.
2. Data Cleaning:

Handling Missing Values: The notebook addresses missing values in numerical and categorical columns. It uses strategies like filling numerical columns with placeholders or medians, and for categorical columns, it uses context-based imputation based on surrounding values.
Handling Duplicates: It identifies and removes duplicate rows to ensure data integrity.
Outlier Detection and Removal: Outliers are detected using Z-scores, and rows with extreme values are removed.
3. Data Preprocessing:

Data Type Conversion: The notebook converts the 'Transaction Date' column to datetime format and ensures numerical columns are of the correct type.
One-Hot Encoding: Categorical variables ('Item', 'Payment Method', 'Location') are one-hot encoded to be used in machine learning models.
Standardization and Normalization: Numerical features are standardized using StandardScaler and normalized using MinMaxScaler.
4. Exploratory Data Analysis (EDA):

Visualizations: The notebook uses various visualizations to explore the data, including histograms, box plots, bar plots, pie charts, and heatmaps.
Insights: The visualizations help identify patterns, distributions, and relationships between variables, such as the distribution of quantity sold, price per unit by item, total spending, payment method usage, and transaction trends over time.
In summary, the notebook takes a raw cafe sales dataset, cleans it, preprocesses it, and then performs EDA to gain insights. The cleaned and preprocessed data is then ready for further analysis or modeling. Let me know if you have any other questions.
