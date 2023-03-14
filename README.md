# Mars Data - Scraping and Analysis - Challenge

## Background

Scraping and analyzing websites with Mars news and weather facts.

## Data Source

1. [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html)

2. [Mars Weather Facts Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

### 1. Part 1: Scrape titles and preview text from Mars news articles.

a. Automated browsing to visit the Mars news site and Extract Data

b. The titles and preview text of the news articles

### 2. Part 2: Scrape and analyze Mars weather data.

HTML table extracted into a Pandas DataFrame

Answers to the following questions:

 - How many months exist on Mars? 12
 - How many Martian days' worth of data are there? 1867
 - Which month, on average, has the lowest temperature? The highest? Highest 8, lowest 3
 
    ![AveragetempByMonth](https://github.com/lintubaby5/webscraping-challenge/blob/main/Images/Temp_by_month.png)
 - Which month, on average, has the lowest atmospheric pressure? The highest? Highest 9, lowest 6
 
    ![AveragepressurebyMonth](https://github.com/lintubaby5/webscraping-challenge/blob/main/Images/Pressure_by_month.png)
 - How many terrestrial days exist in a Martian year? around 700.
 
    ![TempByTerrestrialDate](https://github.com/lintubaby5/webscraping-challenge/blob/main/Images/Temp_by_terrestrial_date.png)
    The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

d. [CSV with the data](https://github.com/lintubaby5/webscraping-challenge/blob/main/Output/mars_weather.csv) 

