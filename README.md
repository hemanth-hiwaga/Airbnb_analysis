# **Case Study on Airbnb Dataset**

## **Introduction**
This case study delves into the analysis of an Airbnb dataset, aiming to uncover valuable insights through exploratory data analysis (EDA) and feature engineering. The goal was to understand price distributions, neighborhood dependencies, and other impactful factors.

---

## **1. Data Exploration**
- **Dataset Overview**: The dataset comprises information about Airbnb listings, including details like price, location, room type, and availability.
- **Missing Values and Duplicates**: Missing values were identified and dropped, as they could not be imputed. Duplicate rows were also removed to ensure data quality.

---

## **2. Key Insights from Exploratory Data Analysis**

### **Price Analysis**
- **Outliers in Price**: An initial analysis revealed significant price outliers. For better visualization, listings with prices above 1500 were excluded, providing clearer insights.
- **Price Distribution**: The price distribution showed that most listings fall within a lower price range, with a steep drop as prices increase.

![](/images/01price_distribution.png)

### **Availability Trends**
- The availability of listings throughout the year was analyzed, revealing interesting distribution patterns. Most listings have limited availability, with fewer properties being available all year round.

![](/images/02_output.png)

### **Neighborhood Insights**
- **Average Price by Neighborhood Group**: The mean prices varied significantly across different neighborhood groups, with certain areas consistently commanding higher prices.
- **Dependency on Room Type**: The room type played a crucial role in determining prices, with entire homes/apartments being priced higher than shared or private rooms.

![](/images/03.png)

---

## **3. Feature Engineering**
- A new feature, **price per bed**, was created to better understand pricing in relation to the number of beds available in each listing. This provided deeper insights into cost efficiency across neighborhoods.

---

## **4. Visualizations and Observations**

### **Geographical Distribution**
- A scatter plot of longitude and latitude highlighted the geographical spread of Airbnb listings, with distinct clusters in popular areas. Room types were visually distinguished, offering insights into the types of accommodations prevalent in specific locations.

![](/images/04.png)

### **Locality and Review Dependency**
- A scatter plot showed the relationship between the number of reviews and pricing, with certain areas having a clear trend where higher prices correlated with more reviews. However, outliers with high prices and few reviews were also present.

![](/images/05)

### **Pair Plot Analysis**
- Pair plots provided a deeper understanding of relationships between variables like price, minimum nights, number of reviews, and availability. For example, some variables showed noticeable groupings or weak correlations.

![](/images/06.png)

### **Correlation Heatmap**
- A heatmap of numerical variables revealed:
  - A positive correlation between price and beds.
  - Other variables, like latitude and longitude, had weaker correlations with price, indicating less direct influence.

![](/images/07.png)

---

## **Conclusion**
This analysis of the Airbnb dataset provided valuable insights into pricing dynamics, geographical trends, and key dependencies. Feature engineering and visualizations enriched the understanding of the dataset, paving the way for actionable recommendations or predictive modeling in future studies.

---
