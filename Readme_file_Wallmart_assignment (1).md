
# Write a scraper to scrape product reviews from a Walmart product link.

## What is web-scraping?

Web scraping is a technique for extracting information from the internet automatically using a software that simulates human web surfing.

 ## How is web-scraping useful?
 
Web scraping helps us extract large volumes of data about customers, products, people, e-commerse sites, etc. It is usually difficult to get this kind of information on a large scale using traditional data collection methods. We can utilize the data collected from a website such as e-commerce portal to understand customer behaviors and sentiments,ratings,opinion about product after purchase, buying patterns, and brand attribute associations which are critical insights for any business.

## Packages used:

1. Salenium
2. Chrome Driver
3. Pandas
4. BeautifulSoup

## Implementation of  the scraper.

To extract data using web scraping with python, you need to follow these basic steps:

1.Find the URL that you want to scrape.

2.Inspecting the Page.

3.Find the data you want to extract.

4.Write the code.

5.Run the code and extract the data.

6.Store the data in the required format. 

## What challenges faced and how did you solve them?

In webscraping correct and usefull data extraction is very important. We can get data using URL is very easy but that HTML page data
contains unwanted tags and symbols.

Challenging task is to detect and remove the tags and make the data readable. So we can extract the 
apropriate text from page.

With the help of of BeatufulSoup library we can easily extract the data from URL page.

While data extraction i seen that, some of the reviews not contain the titles. After extraction data regarding reviews, its seen that the number of reviews not equal to the revies title. Due to this i can able to add the titles in a data frame, beacuse in data frame we need same length or rows of each column/variable.

If we simply decrease/increase column length(title length) and add to data frame it will mismatch data.

## What else you could do to improve your scraper?

I need the number of review titles equal to number of reviews. 
If i can able pass NAN in the list of titles for perticular review which not having title.
Then i can get equal length of all columns and able to add title column in data frame.

## How would you design it to make it work on other retailers as well?

We can used this procedure and codes to extract review data from any other website by doing simple changes in it.
