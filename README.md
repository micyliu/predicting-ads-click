# predicting-ads-click

## Python project working with Kaggle dataset <https://www.kaggle.com/fayomi/advertising/data>.
      The purpose of the project is to whether or perhaps also when a person will click on the ad based on the other input
      variables provided about the person.

## Data Dictionary:
      Input variables:
      1) Daily time on site
      2) Age
      3) Area income
      4) Daily internet usage
      5) Ad topic line
      6) City
      7) Male
      8) Country
      9) Timestamp
      Output variable:
      10) clicked on ad
      

## Exploratory Data Analysis Findngs:
      1) data seemed to be clean with no significant outliers.
      
      2) decided to remove country and city variable because there are too many unique country, city variable combination and
      not enough data points in the same city and country;
      
      3) the strong correlation between daily_internet_usage and daily_time_on_site, Clicked and daily_time_on_site.although
      moderate, there is also correlation between age and daily time on site, and area_income with daily_time on site.
      
      4) The people who clicked on the ad versus the ones that did not click on the ad does seem to be very different from 
      each other in terms of the following variables: daily time on site, age, area income, daily internet usage


## Data Transformation
    1) No significant data transformation was done on the dataset since the data was already clean.
    
    2) Depending on the model ran on the data, appropriate data transformation was done.

## Model comparison with confuson matrix, precision and recall, F-score, precision trade off, ROC AUC curve
   1) Model 1:
   
   
              
   2) Model 2:
   
   
   
   3) Model 3:
   
   
   
## Final Model selection


