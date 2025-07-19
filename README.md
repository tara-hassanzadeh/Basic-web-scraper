# 📰 Web Headline Scraper

This project is a simple Python script that extracts news headlines from web pages. You just provide the URL of the news page, and the script fetches and displays the headlines found inside `<h2>` and `<h3>` tags. It’s a handy tool for practicing web scraping and quickly gathering news headlines.

---

## ⚙️ Features

- Dynamically accepts URL input from the user  
- Extracts headlines from HTML `<h2>` and `<h3>` tags  
- Filters out empty headlines and displays only valid ones  
- Uses a User-Agent header to avoid being blocked by servers  
- Great for practicing basic web scraping concepts  

---

## 🧠 Skills Practiced

- Sending HTTP requests with the `requests` library  
- Parsing and analyzing HTML with `BeautifulSoup`  
- Handling user input with the `input()` function  
- Managing HTTP headers and setting User-Agent  
- Checking HTTP response status codes  
- Extracting and cleaning text data from HTML elements  

---

## 🚀 How to Run

1. **If you don’t have Python installed, install Python 3 first:**  
   Download it from [python.org](https://www.python.org/downloads/).

2. **Install the required libraries:**  
   Open your terminal or command prompt and run:
   
   ```bash
   pip install requests beautifulsoup4
