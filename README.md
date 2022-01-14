# IMDB-Web-Scraping-using-Python

In this project , I am going to scrape a data from IMDB website: top 250 movies

Data link: https://www.imdb.com/chart/top/

Web scraping is the process of extracting data from the website using automated tools to make the process faster.

Here I am scraping the IMDb movie Title, Rank ,Year and Rating with the help of the BeautifulSoup library of Python.

Modules Needed:
Below is the list of modules required to scrape from IMDB.

requests: Requests library is an integral part of Python for making HTTP requests to a specified URL. 

bs4: BeautifulSoup object is provided by Beautiful Soup which is a web scraping framework for Python. It is a Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.

Save data to file:

Finally scraped data is saved to csv file: "IMDB.csv" using csv module.
