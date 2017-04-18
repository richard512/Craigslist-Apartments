# Craigslist-Apartments

This project is aimed at determining a fair market value of a rental listing for an apartment or condo on Craigslist. The project involves building a web scraper for scraping the data for apartment and condo listings from Craigslist. This data is then explored and analyzed by using machine learning algorithms (gradient boosting, kNN).

## Dependencies
```
pip install pandas matplotlib seaborn sklearn BeautifulSoup sqlalchemy pymysql
sudo apt install python-regex
sudo apt install python-mysqldb
```

## How to run it

	python scrape.py

Then it'll pound craigslist with a few thousand HTTP requests... A few minutes later (if it didn't break) it'll spit out a csv file. craigslist_data.csv

	python analyze.py

Now this will churn through that csv file doing stuff that I don't really understand. How does it work, alex3140?