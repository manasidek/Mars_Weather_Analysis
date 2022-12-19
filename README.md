# Mission to Mars

## Overview of the project

- The purpose of the analysis is to scrape, organize, analyze, and visualize the data.

## Sources

- Data: 
    1. [Mars NASA news site](https://redplanetscience.com)
    2. [mars-challenge](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html)

- Softwares: Python 3.7(Splinter and BeautifulSoup), Jupyter Notebook 6.4

## Analysis

### Part 1(Scrape titles and preview text from Mars news articles)

- The link to the script of the analysis is : [Mars_News]()

- The image of the scraping is shown below:

![title_preview]()

- The link to the output file is [mars_news]()

### Part 2 (Scrape and Analyze Mars Weather Data)

- The link to the script of the analysis is : [Mars_Weather]()

- The data from scraping is stored in a dataframe, which is shown in the image below :

![DataFrame]()

- The data was analyzed and data visualization was created:

    1. The Average Temperature per month was calculated.
    
    ![Avg_Temp_month]()
    
    2. The Sorted visualization od average temperature is shown below:
    
    ![Sorted_avg_temp_month]()

    3. The Average Pressure per month was calculated.
    
    ![Avg_pressure_month]()
    
    4. The number of terrestrial days in a martian year.
    
    ![terrestrial_days]()

- The link to the output file is [Mars_Weather_data]()

### Summary

- On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

- Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

- The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot.