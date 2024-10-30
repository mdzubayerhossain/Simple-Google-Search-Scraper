# Simple Google Search Scraper

This Python script allows users to perform a Google search directly from the command line. By entering a search term, the script fetches the first result's description from Google. It's a lightweight and quick way to get search results using Python's `requests` and `BeautifulSoup` libraries.

## Features
- Command-line interface for user input
- Retrieves the top search result for any query
- Uses `requests` to fetch web data and `BeautifulSoup` to parse HTML

## Requirements
- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
1. Navigate into the project directory:
   ```bash
   cd Simple-Google-Search-Scraper
1. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4
Usage
3  Run the script and enter a search term when prompted:
   ```bash
   python app.py
Input:
> python your_script.py
> Enter your search query: "Python programming"

Output:
> Python is an interpreted high-level general-purpose programming language.

