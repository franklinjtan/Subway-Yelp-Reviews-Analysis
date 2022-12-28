# Subway Yelp Reviews Analysis

## Summary
* Created a set of analyses that support or disprove the following statements made by company leadership:
  * Head of Customer Service: “Our ratings are gradually improving, and we will soon reach 4.5/5.”
    * Overall, the data and visualizations do not fully support the statement by the Head of Customer Service and may actually be more suited to support the opposite conclusion.
    
  * Head of Store Operations: “Sandwiches are a tricky business. All sandwich chains suffer from poor customer ratings.”
    * There is data to suggest that sandwiches are not the only tricky business.
  
  * Head of Social Media: “The goal of 4.5/5 is unreasonable for national chains like us. Only small, local, and boutique restaurants can achieve such high ratings.”
    * While the bar chart indicates that the statement by the Head of Social Media is true, further examination such as the plotting of a scatter plot is required to explore if there is a strong relationship between restaurant size and average ratings.
    * There is also an issue of overrepresentation of local restaurants over boutique and national-sized restaurants exist as can be seen by this relative frequency table:
    
  * Chief Data Scientist: “It is well known that customers make the effort to give a rating only when they are either extremely angry or absolutely delighted with the service. So online ratings are not reliable.”
    * The data also supports the statement for all years from 2018 to 2021. In the bar chart for Ratings vs Number of Reviews for 2018-2021, we can see that ratings of 1 and 5 are abundant compared to 2, 3, and 4. Therefore, there is further evidence to support the statement by the Chief Data Scientist: “It is well known that customers make the effort to give a rating only when they are either extremely angry or absolutely delighted with the service.”
  
* Yelp Datasets used in the analysis: reviews.csv and restaurants.csv

## Procedure
* Imported 5-Year adjusted closing prices of my stock investments using Yahoo Finance 
* Extracted percent change using NumPy
* Used linear regression to calculate slope (beta) and correlation
* Plotted % returns and linear regression line
* Created a correlation matrix and heatmap

## Screenshot of Data Visuals Generated


## Related Course
* Cornell University MSBA BANA 5440 Statistical Programming with Rakesh Allu, Ph.D. Student, Operations, Technology & Information Management

## Libraries Used
* [Matplotlib](https://matplotlib.org/stable/tutorials/index)
* [NumPy](https://numpy.org/doc/stable/)
* [Pandas](https://pandas.pydata.org/)
* [SciPy](https://scipy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Datetime](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)
