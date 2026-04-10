# Codveda-Data-Analytics-Internship
Data Analytics internship projects completed through Codveda Technology.

## About Me
Product Manager and Data Analyst with hands-on experience in AdTech, Fintech, and marketplace development. This internship focused on building advanced data analytics skills using Python, machine learning, and visualization tools.


## Level 1 - Basic Data Analytics

### Task 1: Data Cleaning and Preprocessing
**Dataset:** Amazon Sale Report.csv (128,975 rows, 24 columns)

**Objectives Completed:**
- Loaded dataset using pandas
- Dropped high-missing columns: fulfilled-by, promotion-ids, Unnamed: 22
- Filled missing values: Courier Status (mode), currency (mode), Amount (median), ship columns (Unknown)
- Removed duplicates: 0 found
- Standardized Date column to datetime64
- Standardized categorical columns to Title Case

**Output:** Amazon_Sales_Cleaned.csv

**Tools Used:** Python, pandas


### Task 2: Exploratory Data Analysis (EDA)
**Dataset:** Amazon Sales Cleaned (128,975 rows)

**Objectives Completed:**
- Calculated summary statistics (mean, median, mode, standard deviation)
- Analyzed categorical data distributions
- Identified correlations between numerical features
- Created professional data visualizations

**Key Findings:**
- 60% successful order completion rate (77,804 shipped orders)
- 14% cancellation rate (18,332 cancelled orders)
- Top product categories: Sets (50,284), Kurta (49,877), Western Dress (15,500)
- Most popular sizes: M, L, XL

**Tools Used:** Python

### Task 3: Basic Data Visualization

**Objectives Completed:**
- Created bar plots, line charts, scatter plots, histograms, and box plots
- Applied professional styling with custom colors, labels, and titles
- Exported high-resolution visualizations at 300 DPI

**Tools Used:** Python

## Level 2 - Intermediate Data Analytics

### Task 1: Regression Analysis
**Target:** Amount (INR), **Feature:** Quantity

**Objectives Completed:**
- Split dataset 80/20 into training and testing sets
- Fitted a Linear Regression model using scikit-learn
- Interpreted model coefficients and evaluated performance

**Results:**
- R-squared: 0.0408
- RMSE: 266.56
- Coefficient: 525.01

**Interpretation:** Quantity alone is a weak predictor of Amount. Other factors like Category and product type drive price more significantly.

**Tools Used:** Python


### Task 3: Clustering Analysis (K-Means)
**Features:** Quantity and Amount

**Objectives Completed:**
- Standardized features using StandardScaler
- Applied K-Means clustering
- Determined optimal K=3 using the Elbow Method
- Visualized clusters using 2D scatter plots

**Results:**
- Cluster 0: 70,930 orders, avg 495 INR (Budget segment)
- Cluster 1: 42,392 orders, avg 937 INR (Mid-range segment)
- Cluster 2: 379 orders, avg 1,291 INR (Bulk/Premium segment)

**Tools Used:** Python

## Level 3 - Advanced Data Analytics

### Task 1: Predictive Modeling (Classification)
**Target:** Shipped vs Not Shipped (binary classification)
**Features:** Qty, Amount, Category, Size, Fulfilment (encoded)

**Objectives Completed:**
- Preprocessed data with label encoding and feature scaling
- Trained and evaluated 3 classification models
- Performed hyperparameter tuning using GridSearchCV

**Results:**
- Logistic Regression: Accuracy 94%, F1 0.97
- Decision Tree: Accuracy 94%, F1 0.97
- Random Forest: Accuracy 94%, F1 0.97
- Best GridSearch params: max_depth=5, n_estimators=50, F1=0.9704

**Tools Used:** Python

### Task 2: Dashboard (Power BI)
**Dataset:** Amazon_Sales_Cleaned.csv

**Objectives Completed:**
- Imported and cleaned dataset in Power BI
- Created interactive visualizations
- Set up slicers and filters for interactive exploration
- Published dashboard

**Visuals Built:**
- Total Revenue and Total Orders (KPI cards)
- Sales Amount by Category (bar chart)
- Orders over Time (line chart)
- Order Status Distribution (donut chart)
- Orders by Ship State (map)
- Slicers: Category, Size, Fulfilment
  
  <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/6e7a757f-8cf7-4baf-998d-32f1812cb53f" />
  


**Tools Used:** Power BI Desktop

## Skills Developed
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical analysis and regression modeling
- K-Means clustering and segmentation
- Classification modeling and hyperparameter tuning
- Interactive dashboard design
- Python programming
- Business insights extraction

## Contact
**Nanret Kromtit**
- LinkedIn: [www.linkedin.com/in/nanret-kromtit-4692a7282](www.linkedin.com/in/nanret-kromtit-4692a7282)
- Email: napasat66@gmail.com
- GitHub: [github.com/kromtit-Nanret](https://github.com/kromtit-Nanret)

This internship is part of Codveda Technology's Data Analytics program.
#CodvedaJourney #CodvedaExperience #FutureWithCodveda
