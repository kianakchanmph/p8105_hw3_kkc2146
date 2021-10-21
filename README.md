# p8105_hw3_kkc2146
 Homework 3 for Data Science, P8105 Kiana Chan 

#PROBLEM 1 

Load the Instacart data:

library(p8105.datasets)
data("instacart")

## This data contains 1384617 total observations. Some key variables include order ID, product ID, order number, and product name, describing the various instacart orders. 

How many aisles are there, and which aisles are the most items ordered from?

```{r}
instacart_df %>% 
    group_by(aisle)
```




Make a plot that shows the number of items ordered in each aisle, limiting this to aisles with more than 10000 items ordered. Arrange aisles sensibly, and organize your plot so others can read it.





Make a table showing the three most popular items in each of the aisles “baking ingredients”, “dog food care”, and “packaged vegetables fruits”. Include the number of times each item is ordered in your table.

Make a table showing the mean hour of the day at which Pink Lady Apples and Coffee Ice Cream are ordered on each day of the week; format this table for human readers (i.e. produce a 2 x 7 table).
