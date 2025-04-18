# Python_EDA_TitanicDataSet

EDA stands for Exploratory Data Analysis. In this project, I performed EDA on a sample Titanic dataset consisting of 500 passenger records. The dataset includes key features such as name, sex, age, and survival status.

The Titanic dataset is one of the most well-known datasets in the data science community. It documents real passenger data from the Titanic tragedy in 1912, and it's commonly used to explore classification problems and uncover insights from structured data.

**Goals**
1. Investigate the structure and content of the Titanic dataset.
2. Generate statistical summaries and analyze key patterns.
3. Detect and handle duplicate entries and missing values.
4. Identify potential insights that can influence survival chances.

**EDA Process**
A. Initial Exploration:
  1. Displayed the dataset using .head(), .tail(), and .sample().
  2. Used .info() to get data types and null counts.
  3. Dataset contains 500 rows and 4 columns: survived, name, sex, age.

B. Statistical Summary:
  1. Average age: ~35.9 years, with a minimum of 0.67 and maximum of 80.
  2. 54% of passengers in this sample survived (survived = 1).
  3. Categorical breakdown: 288 males and 212 females.

C. Duplicates:
  - Detected 1 duplicate row, which was removed during cleaning.

D. Missing Values:
  1. Column age has 49 missing values (~9.8% of the dataset).
  2. Potential handling methods: mean/median imputation, or grouping by sex or survived.

**Insights**
1. A majority of the passengers in this sample survived.
2. Most passengers are male, but survival may vary based on gender and age.
3. The name field contains titles (Mr., Miss, etc.) which can be useful for further feature engineering.
4. Age distribution is quite wide, ranging from infants to elderly, which can affect survival chances.

**Advice for Future Work**
1. Extract titles from the name column to create a new categorical feature.
2. Use grouping (e.g., by sex, title) to impute missing age values more accurately.
3. Build visualizations such as survival rates by gender and age to strengthen the analysis.
4. This dataset is great for training simple classification models—logistic regression, decision trees, etc.

📫 Feel free to connect or reach out if you have suggestions, feedback, or want to collaborate:
📧 helenpatricia061006@gmail.com
🔗 linkedin.com/in/helenptrcia

#Python
#EDA
#Titanic
#DataScience
#ExploratoryDataAnalysis
