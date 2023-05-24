Mikail Alejandro and An Tran's PROPEL project submission

Video: https://youtu.be/cGXgtchnE3c

We used a dataset that provides a breakdown of the nutritional content of fast food items from eight different popular chains. From this data, we wanted to ask the question, how does the nutritional content of fast food items differ between franchises?

First, we loaded the tidyverse package in R in order to manipulate and visualize the data. We then saw on the FDA website that the total calories, saturated fat, sodium, and sugar content had the most adverse health effects, so we then cleaned up the data to only include those four categories (along with restaurant and menu item) using the "select" function.

We then plotted this cleaned information via boxplots to see the distributions of our nutritional categories for each restaurant and to also spot any potential outliers. We used the "ggplot" and "geom_boxplot" functions. We also found the descriptive statistics for each category and restaurant using the "group_by" and "summarize" functions.

After this, we created scatter plots comparing total calories to the other three categories to see if there was any correlation between them using the "gglot" and "geom_point" functions.

We then wanted to see which fast restaurant contributed the most menu items to each of our four categories, so we isolated the top 20 items in each category using the "arrange", "slice" and "select" functions and created pie charts using the "pie" function. After this, we found the top 3 menu items that contained the highest amount per category, which was done using "slice" and "select."


Citations:
https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition
https://www.fda.gov/food/new-nutrition-facts-label/how-understand-and-use-nutrition-facts-label#:~:text=Saturated%20fat%2C%20sodium%2C%20and%20added%20sugars%20are%20nutrients%20listed%20on,nutrients%20to%20get%20less%20of
https://r-graph-gallery.com
