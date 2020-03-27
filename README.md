This project involved the analysis of the housing data measured by the King County Council between 2014 - 2015. The dataset as it was given had some messy and missing data that required initial cleaning such as the converting of some rows to numerical values while accounting for null or missing values. 
Three business questions were devised:
-What cities are the most expensive houses in the given dataset ; which required the classification based on cities found using the zip codes in the dataset.
-Is there significant evidence that renovating a house increases its price; which required running a t-test on the prices of  houses that have been renovated recently.
-Does time have an effect on the housing prices in King County; found through duplicate ids with different date and price values indicating houses bought and sold within the same year.
​
​
After splitting the data into test and train some simple regression models were run on the data to see the effect on the price. These included single variable    regression as well as multi variable regression to determine suitable model with a low prediction error. Some of the test that were run where standardised based on z scores to help visualise the results on the same level.
​
The final R2 ran on the test data yielded an R2 of 0.55.
