# California Housing Price Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the California Housing dataset to understand the key factors influencing housing prices. The analysis includes data cleaning, visualization, and feature engineering to extract meaningful insights from the data.

---

## 🎯 Objectives
- Understand the distribution of key variables  
- Handle missing values appropriately  
- Analyze relationships between features  
- Perform feature engineering  
- Identify key factors affecting house prices  

---

## 📊 Dataset Description
The dataset contains demographic, geographic, and housing-related features for different regions in California.

- **median_income**: Median income of households  
- **housing_median_age**: Median age of houses  
- **total_rooms**: Total number of rooms  
- **total_bedrooms**: Total number of bedrooms  
- **population**: Total population  
- **households**: Number of households  
- **median_house_value**: Median house price (target variable)  
- **latitude & longitude**: Geographic location  
- **ocean_proximity**: Proximity to ocean (categorical)  

---

## 🔍 Analysis Performed
- Distribution analysis using histograms  
- Relationship analysis using scatter plots  
- Handling missing values  
- Feature engineering (ratio-based features)  
- Correlation analysis  
- Outlier detection  

---

## 🧠 Feature Engineering
New features were created to extract more meaningful insights:

- **rooms_per_household** = total_rooms / households  
- **bedrooms_per_room** = total_bedrooms / total_rooms  

These features help in understanding housing density and structure.

---

## 📈 Key Insights

- Median income is the **strongest predictor** of house prices  
- Strong positive relationship between income and house value  
- Dataset contains capped values (house price ~500,000 and age ~52)  
- Coastal regions have higher population density and income levels  
- Presence of skewed distributions and outliers in the data  

---

## 📊 Visualizations

### Distribution of Median Income
![Income Distribution](images/median_income_hist.png)

### Income vs House Price
![Income vs Price](images/income_vs_price.png)

### Correlation Heatmap
![Heatmap](images/correlation_heatmap.png)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure
