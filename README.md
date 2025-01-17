# King County Housing's Reigning Features
Authors: Brian Matsiko, Erin Vu

# Table of Contents
1. Overview
2. Business Problem
3. Data
4. Recommendations
5. Conclusion
6. For More Information

# 1. Overview

In this notebook, we will be exploring the Kings County real estate sales data to identify key features that drive prices up in housing sales in order to maximize the market value of a home to sell for the highest profit margin. In identifying these key features, we can recommend to remodel houses or multifamily units, and focus on these features in new developments to increase their value to rent and sell at higher prices, maximizing profits. We used Python to clean and preprocess the data, execute exploratory data analysis, and build simple linear regression models.

# 2. Business Problem

Our stakeholders at Seattle Rental Group offers services for not only property owners but also to renters and buyers. Their property owner service side will help you lease or sell your home or multifamily property. Properties will have many different facets that will be more or less attractive to buyers and renters which impacts the market value. We want to know how we can advise Seattle Rental Group to apply features to their properties and new developments and advise property owners who use their services to remodel and upgrade their properties to maximize the market value of the property to sell or lease. The initial features we believe have an impact on prices are square feet of the property, the age of the property, and whether or not the property is waterfront and will explore those first.

# 3. Data

- The source for this data is from the official government website of King's County for housing sales in 2014-2015.
- The data is relevant for our analysis because we are focusing in the King's County area and this set has information about housing sales in King's County.
- The data set includes 21,597 records 21 features
- Our target variable is sale price
- Features included:
-     -house id, 
      -sale date, 
      -sale price, 
      -bedrooms, 
      -bathrooms, 
      -square footage of home, square footage of the lot, 
      -how many floors, 
      -waterfront or not, 
      -view rating, grade of house, 
      -square footage above the basement, 
      -square footage of the basement, 
      -the year the house was built,
      -the year the house was renovated, 
      -the zip code of the house, 
      -the latitude and longitude, 
      -square footage of the living space for the nearest 15 neighbors
      -square footage of lot for the nearest 15 neighbors
      
- https://info.kingcounty.gov/assessor/esales/Residential.aspx

# 4. Methods 

- We started off by importing the data and looking at the data
- We then identified our numerical/continuous variables and our categorical variables
- We cleaned our data in Python and then visualized our data through histograms and correlation plots with Seaborne and Matplotlib
- We then used Stats Models and ScikitLearn to build our first simple linear regression model
-   First simple model: Target was price and our variable was sq ft of l iving area as it had the highest correlation to price
- After our first model, we added, transformed, and engineered new features to ssee how they impact price

We believe that this approach is appropriate as our goal of our analysis is to see what features drive sale price up so we can focus on remodelling or upgrading to those features.

# 5. Results








# 6. Conclusions

We found that these ____________ features had the greatest impact on sale price of houses in King County of Washington. We recommend that our stakeholder remodel, upgrade, and develop properties to have these features as they increase the sale price. Our stakeholder can also communicate these findings to property owners who use their services to lease or sell their own properties. Our model might not fully solve the business problem as our data might only include home sales and not multifamily buildings. We also lack a full understanding of the neighborhoods and how they are perceived. Other ways our model might be incomplete are the other amenities a house might have not included in the data, such as ac/heater systems, appliances, type of flooring, or attics. In the future, we can add to our model by adding data on mutlifamily building sales as well as trying to find out more information on specific housing amenities and neighborhood perception that might impact the sale price.

# 7. For More Information

Please review our full analysis in our Jupyter Notebook and our Presentation

For additional questions, please contact:

Brian Matsiko at

Erin Vu at erin.vu94@gmail.com
