# MAIN-PROJECT
# 🚗 Electric Vehicle Population Data Analysis Using Python
## 📌 PROJECT OVERVIEW
This project focuses on analyzing **Electric Vehicle (EV) Population Data** using Python and Pandas. The dataset contains information about electric vehicles, including vehicle make and model, model year, electric range, vehicle type, location, and other related details.

The project involves **data loading, data cleaning, preprocessing, exploratory data analysis (EDA), and data visualization**. The preprocessing stage includes handling missing values, removing duplicate records, correcting data types, standardizing categorical values, detecting potential outliers, and creating derived columns.

The analysis aims to understand EV characteristics, distribution, electric range, manufacturers, model years, and geographic patterns. The cleaned dataset and analysis can provide useful insights into the electric vehicle population and its characteristics.
## 🎯 Aim of the Project

The main aim of this project is to analyze the characteristics and distribution of electric vehicles and identify useful patterns related to:

Electric vehicle types

Vehicle manufacturers and models

Model years

Electric driving range

Geographic distribution

CAFV eligibility

Relationship between model year and electric range

## 🎯 Project Objectives

Import and understand the EV dataset using Pandas.

Identify the number of rows and columns and understand the data types.

Handle missing values and duplicate records.

Correct inappropriate data types.

Standardize categorical values where necessary.

Detect potential outliers using the IQR method.

Create derived columns for further analysis.

Perform univariate, bivariate, and multivariate analysis.

Use groupby, pivot tables, and correlation analysis.

Create meaningful visualizations to identify patterns and trends.

Generate useful insights from the analysis.

## 🔧 Workflow

### 1. Data Loading & Initial Overview
Loaded the dataset with Pandas and inspected it using .shape, .info(), .head(), .tail() and .describe().

### 2. Data Cleaning & Preprocessing
 
 Handling missing values
 
 Removing duplicates
 
 Correcting data types
 
 Creating derived columns
 
 Filtering or aggregating data

 ### 3. Exploratory Data Analysis
 Univariate, bivariate, and multivariate analysis

 Use groupby, pivot tables, and correlation analysis
 
 statistical summaries 

 ## 4. Visualization
 10 visualizations using Matplotlib, Seaborn and Plotly: pie charts, histograms, a box plot, bar charts,Stacked Bar Chart,Linechart, scatter plots and heatmaps,correlation matrix

 ## 5.Insight Generation
 The analysis helped identify important patterns and trends in the electric vehicle dataset, including EV types, manufacturers, model years, electric range, and geographic distribution. These insights can support data-driven decisions related to EV marketing, product development, charging infrastructure, and business strategy.

 ## 🔎 Key Findings
Battery Electric Vehicles (BEVs) form the majority of the dataset compared with Plug-in Hybrid Electric Vehicles (PHEVs).

Tesla is the most frequently represented manufacturer in the dataset.

The dataset contains a large number of vehicles from recent model years, particularly around 2023–2026.

The dataset is heavily concentrated in Washington State, so it should not be treated as a balanced representation of EVs across the 

entire United States.

Electric range has a highly skewed distribution, with a considerable number of records having a recorded range of zero.

BEVs generally show higher recorded electric-range values than PHEVs, although zero-range records affect the comparison.

Correlation analysis indicates a relationship between model year and recorded electric range, but the result should be interpreted 
carefully because of the large number of zero-range values.

## 🛠️ Technologies Used
Python

Pandas – Data loading, cleaning, transformation, and analysis

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualization

Jupyter Notebook – Development and analysis environment

GitHub – Project documentation and version control

## 💼  Business Recommendations
### Focus on the growing BEV market:
Since BEVs represent the majority of vehicles in the dataset, EV manufacturers and dealers should focus on increasing their BEV product offerings, marketing, and customer awareness.

### Develop products with better electric range:
The analysis shows considerable variation in electric range. Manufacturers can focus on improving battery technology and driving range to address customer concerns about charging frequency and long-distance travel.

### Target newer EV models:
The high representation of recent model years suggests strong interest in newer EVs. Dealers can focus their marketing and inventory strategies on newer models with improved features, technology, and range.

### Use manufacturer-level insights for competitive strategy:
Tesla has a very large representation in the dataset. Other manufacturers can use this information to identify opportunities to compete through better range, pricing, technology, charging convenience, and customer experience.

### Identify high-potential cities:
The city-level analysis shows that EV registrations are concentrated in certain locations. EV businesses can prioritize these areas for dealerships, charging infrastructure, service centers, and targeted marketing campaigns.

### Expand charging infrastructure strategically:
Businesses and charging-network operators can use geographic EV concentration to identify areas where additional charging stations may have greater potential demand.

### Consider vehicle type when planning marketing:
Since BEVs and PHEVs have different characteristics, businesses should use different marketing strategies for each vehicle type rather than treating all EV customers as one group.

### Use CAFV eligibility in customer targeting:
CAFV eligibility information can help dealers and businesses communicate relevant incentives, eligibility benefits, and purchasing information to potential customers where applicable.

### Improve data quality for better decision-making:
The analysis identified missing values and unusual values, particularly in the electric-range data. Organizations should maintain accurate and complete vehicle data to improve forecasting, customer analysis, and business decisions.

### Use data-driven location planning:
Because the dataset is heavily concentrated in Washington State, businesses operating in that market can use the available geographic information to plan inventory, charging facilities, maintenance services, and promotional activities.

### Monitor EV market trends continuously:
Businesses should regularly analyze model year, manufacturer, vehicle type, electric range, and geographic trends to identify changes in customer preferences and adjust their strategies accordingly.

### Build customer segments using EV characteristics:
Companies can segment customers based on factors such as vehicle type, model year, range, location, and manufacturer. This can support more targeted marketing and personalized offers.

## 🚀 Conclusion

This project demonstrates how Python can be used to clean, analyze, visualize, and extract meaningful information from a large electric vehicle dataset. The analysis provides an understanding of EV types, manufacturers, model years, electric range, and geographic distribution.

The project also demonstrates practical Data Analyst skills, including data preprocessing, exploratory data analysis, statistical analysis, visualization, and insight generation.

## 📁 Repository Structure
├── data/
│   └── export.csv     # original dataset (as downloaded)
├── notebook/
│   └── Electric Vehicle Adoption And Market Analysis.ipynb       # full analysis notebook
├── README.md

## 👩‍💻 Author

Varsha C P

Data Analytics | Python | Pandas | Power BI | Data Visualization
