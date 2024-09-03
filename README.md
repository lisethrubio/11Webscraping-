# 11Webscraping-

## Overview of the Analysis

This assignment is divided into two main parts: web scraping and data analysis using Python. The first part focuses on gathering the latest news articles from the Mars News website. The task is carried out in the Jupyter Notebook titled *`"part_1_mars_news.ipynb"`*, which uses automated browsing to visit the Mars news site. The goal is to identify and extract the titles and preview texts of news articles using *`Beautiful Soup`*. These extracted elements are stored in Python dictionaries, each containing a title and its corresponding preview. All the dictionaries are then collected into a list named *`"article_list"`*. 

The second part of the assignment involves scraping and analyzing Mars weather data from a webpage that features a table of temperature readings from the Curiosity rover. This task is carried out in the Jupyter Notebook titled *`"part_2_mars_weather.ipynb"`* notebook, where *`Beautiful Soup`* is used to scrape the data from the HTML table. The extracted data includes columns like terrestrial date, Martian sol (day), solar longitude, Martian month, minimum temperature, and atmospheric pressure. The extracted rows of data are stored in dictionaries. All the dictionaries are then collected into a list named *`"all_rows_list"`*. Finally, this data is then collected into a Pandas DataFrame named *`"mars_temperature_df"`*, and the data types are converted to the appropriate *`datetime`*, *`int`*, and *`float`* data types.

The analysis portion of the project involves answering key questions about Martian weather patterns. This includes calculating and visualizing the average minimum temperatures to determine the coldest and warmest months on Mars, as well as identifying which months have the highest and lowest atmospheric pressure. Additionally, the length of a Martian year in Earth days is estimated by analyzing the daily minimum temperature patterns over time. These insights are visualized using bar charts and line plots. Finally, the cleaned and analyzed data is exported to a CSV file named *`"mars_temperature.csv"`* stored in the *`"Output"`* folder. This part of the assignment deepens the understanding of Mars' climate and enhances data manipulation and analysis skills using Pandas.

## Results 

The data analysis provided the following insights:

- Number of months on Mars: 12
- Total Martian days' worth of data: 1,867
- Month with the lowest average temperature: Month 3
- Month with the highest average temperature: Month 8
- Month with the lowest average atmospheric pressure: Month 6
- Month with the highest average atmospheric pressure: Month 9
- Number of terrestrial days in a Martian year: Approximately 1,800


## Summary 


This analysis involved two key tasks: scraping and analyzing data related to Mars. The first task focused on extracting the latest news articles from the Mars News website, with titles and preview texts stored in a Python list of dictionaries. The second task involved scraping weather data from a Mars temperature site, organizing the data into a Pandas DataFrame, and converting it to appropriate data types. The analysis revealed that Mars has 12 months, with data covering 1,867 Martian days. The coldest month is Month 3, while the warmest is Month 8. The lowest atmospheric pressure occurs in Month 6, and the highest in Month 9. Additionally, a Martian year is approximately 1,800 Earth days. The cleaned data was exported to a CSV file named *`"mars_temperature.csv"`*, stored in the *`"Output"`* folder, for further use.