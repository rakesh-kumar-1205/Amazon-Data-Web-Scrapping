# Amazon Data Web Scraping

🛒🔍 This Python script scrapes product information from Amazon's website related to PlayStation 5.

## Description

The script performs the following tasks:
- Sends an HTTP request to the Amazon search page for PlayStation 5.
- Extracts product links from the search results.
- Sends HTTP requests to each product page to extract details such as title, price, rating, reviews, and availability.
- Stores the extracted data in a Pandas DataFrame.
- Cleans the data by removing rows with missing titles.
- Saves the cleaned data to a CSV file named `amazon_data.csv`.

## Prerequisites

Before running the script, ensure you have the following installed:
- Python (version 3.6 or higher)
- Required Python packages: `requests`, `beautifulsoup4`, `pandas`, `numpy`

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/rakesh-kumar-1205/Web--Scrapping.git
2. Navigate to the project directory:
    ```bash
   cd Web--Scrapping   
3. Install the required Python packages:
    ```bash
    pip install requirements.txt
4. Run the Python script:
   ```bash
   python Webscraping.py
5. After execution, check the amazon_data.csv file for the scraped data. 📊📋

## License
# This project is licensed under the MIT License. 📜
