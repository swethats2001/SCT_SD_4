# SkillCraft Technology Internship Task
--------------------------------------------
E-Commerce Data Scraper
--------------------------------------------
This Python program extracts product information (such as names, prices, and ratings) from an e-commerce website and saves the data in a structured format as a CSV file. It is an excellent tool for learning web scraping and automating data collection from online stores.

## Features
- Scrapes product **names**, **prices**, and **ratings** from an e-commerce site.
- Saves the extracted data into a structured **CSV file** (`products.csv`).
- Built using Python with `requests`, `BeautifulSoup`, and `pandas` libraries.

## Prerequisites
- Python 3.x installed on your system.
- Required Python libraries: `requests`, `BeautifulSoup4`, and `pandas`.

## How It Works
>The program sends an HTTP request to the e-commerce website.
>It parses the HTML of the webpage using BeautifulSoup.
>Product details like name, price, and ratings are extracted using CSS selectors (based on the website’s structure).
>The collected data is saved into a products.csv file for easy access and analysis.

