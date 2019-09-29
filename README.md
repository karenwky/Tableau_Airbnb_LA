# Tableau: Airbnb(Los Angeles)
With data provided by [Inside Airbnb](http://insideairbnb.com/get-the-data.html), an interactive dashboard is created for customers based on accommodation features. <br/>
![dashboard1](/images/dashboard1.gif)

## Data Source
1. [listings.csv.gz](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/data/listings.csv.gz)<br/>
Detailed listings data such as amenities, zip code and room type. 

2. [listings.csv](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/visualisations/listings.csv)<br/>
Summary information and metrics for listings sucha as name, price and number of reviews. 

3. [reviews.csv](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/visualisations/reviews.csv)<br/>
Date of review and listing id. 

## Data Preprocessing
1. Create new boolean features for amenities. <br/>
   <img src="/images/amenities.png" alt="amenities" width=500>

2. Select features from each dataset. 
   ![listing2_features](/images/listing2_features.png)
   <img src="/images/listings_features.png" alt="listings_features" width=700>
   <img src="/images/reviews.png" alt="reviews" width=400>

3. Narrow down the dataset by selecting zip codes of 2 different areas. 

   |  | Hollywood Boulevard |	
   |---|---| 
   | 90019, 90035, 90036 | South Robertson |
   | 90046, 90069 | West Hollywood |
   | 90048 | Carthay |
   | 90068 | Hollywood Dell |
   | | |
   | | **Bay side** |
   | 90058 | Vernon |
   | 90066, 90230, 90292, 90293 | Marina del Rey |
   | 90291 | Venice |
   | 90401, 90402, 90403, 90404, 90405 | Santa Monica |
   
## Interactive Dashboard
![dashboard2](/images/dashboard2.gif)
Customers can easily find the ideal accommodation by selecting different criterias, such as `amenities`, `room type`, `bed type` and `price`.  

## Detailed Presentation
* Check out worksheets and dashboard with [Tableau Workbook](./airbnb_la.twb). 
* Check out complete code with [Jupyter Notebook](./code). 

## Skills Acquired
* Pandas: e.g. cleaning data, creating new tables and features
* Tableau: e.g. using filters, parameters and pages to create interactive dashboard
