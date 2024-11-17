# SC1015-miniproject
## Monthly Sales Prediction with Online Retail Data

#### Project Overview
This project aims to predict monthly sales quantities for individual products in an online retail. 
The dataset from Kaggle:
https://www.kaggle.com/code/ekrembayar/rfm-analysis-online-retail-ii. 
By leveraging various machine learning techniques, the project provides data-driven insights to optimize inventory management, forecast revenue, and inform marketing strategies.

#### Dataset

- Invoice details (Invoice code, Date)
- Product information (StockCode, Description, Price)
- Customer details (CustomerID, Country)
- Sales metrics (Quantity, Price)
    
We focus on monthly aggregation to capture trends and seasonality in product sales.

### Steps in the Project

###### Exploratory Data Analysis (EDA)
Cleaned the dataset by handling missing values, removing duplicates.  
Aggregated sales data to monthly levels for product-specific trends.  
Identified key trends, such as seasonality and product performance.  

###### Trend-Based Product Clustering
Products were grouped based on their sales trends across months:  
Applied cosine similarity to identify similarities in product sales patterns.  
Used hierarchical clustering to segment over 5,000 products into 5 meaningful clusters.  

###### Modeling Approach
Selected Random Forest Regression as the prediction model due to its ability:  
Capture non-linear relationships between features.  
Effectively handle categorical variables like product categories.  
Provide insights into feature importance.  

###### Model Outcomes
The model successfully captured the general sales trends and provided accurate predictions of monthly sales quantities.  

Feature importance analysis revealed:   
Product categories (Category 3) and specific months (February) significantly influenced sales.   

Monetary Value Estimation    
Combined predicted sales quantities with average monthly prices to estimate monetary sales values, providing realistic revenue projections.    

##### Key Insights    
Trend-Based Clustering: Products grouped by sales patterns help tailor inventory and marketing strategies.
Seasonality Effect: February emerged as a high-demand period, suggesting the need for targeted planning.
Feature Impact: Product categories and seasonal features heavily influence sales, offering actionable insights for promotions and campaigns.    

Recommendations     

Seasonal Adjustments:   
Focus on February’s demand spikes by increasing inventory and running seasonal campaigns.   
Category-Specific Strategies:    
Prioritize Category 3 products, as they significantly impact overall sales performance.   


Extended Analysis:    
Integrate external factors like holidays, promotions, and regional preferences for richer predictive power.   
### Contributors
@serraisik5 : Data preparation, Modeling, Outcomes   
@derenolgun : EDA, Insights, Presentation




