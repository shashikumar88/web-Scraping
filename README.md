# Web Scraping Project

## Overview
This project demonstrates web scraping using Python with `requests` and `BeautifulSoup`. The script extracts product information from a sample webpage and stores it in a CSV file.

## Technologies Used
- Python
- `requests` library for making HTTP requests
- `BeautifulSoup` from `bs4` for parsing HTML
- `pandas` for data manipulation

## How It Works
1. The script fetches the HTML content of the webpage.
2. It parses the HTML using `BeautifulSoup` to extract product details.
3. The extracted data is cleaned and structured into lists.
4. A Pandas DataFrame is created to store the data.
5. The data is saved as a CSV file named `products.csv`.

## Installation
To run this script, ensure you have the required dependencies installed:
```bash
pip install requests beautifulsoup4 pandas
```

## Usage
Run the script using Python:
```bash
python script.py
```
This will generate a `products.csv` file containing the extracted product data.

## Sample Output
The extracted data is stored in `products.csv` with the following columns:
- Name
- Price
- Stock

Example:
```csv
Name,Price,Stock
Apple,3.00,50
Banana,1.50,100
Cherry,2.70,80
Pineapple,2.00,25
```

## License
This project is for educational purposes only.

