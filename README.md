# 💻 Amazon Laptop Scraper 🛒

This repository contains a Python-based web scraping project that extracts laptop specifications (name, price, rating, and image URL) from Amazon India's search results for laptops under ₹50,000.

### 📄 Project Description

The **Amazon Laptop Scraper** is designed to scrape multiple pages of Amazon search results and gather information about laptops. The following details are extracted:

- **Laptop Name**
- **Price**
- **Customer Rating**
- **Image URL**

The project fetches data from multiple pages (up to 20) and stores it in a clean, structured format using a **Pandas DataFrame**. The extracted data can be further analyzed or used for other purposes, such as price comparison, building a recommendation system, or creating datasets for machine learning models.

### 🚀 Features

- **Multi-Page Scraping**: The scraper iterates through multiple pages of Amazon search results (by default, 20 pages).
- **Data Filtering**: It ensures that only laptops priced under ₹50,000 are collected.
- **Data Structuring**: All data is stored in a structured format using a dictionary and later converted into a Pandas DataFrame for easy analysis.
- **Duplicate Handling**: The project includes functionality to remove any duplicate entries that might be collected during the scraping process.

### 📦 Dependencies

The project uses the following Python libraries:

- **Pandas**: For structuring and cleaning the extracted data.
- **BeautifulSoup (bs4)**: For parsing the HTML and extracting relevant data.
- **Requests**: For sending HTTP requests to retrieve the HTML content from Amazon.

You can install the necessary dependencies using `pip`:

```bash
pip install pandas beautifulsoup4 requests
