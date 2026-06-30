 Quotes Web Scraper

 Project Description
This project is a simple Python web scraper that extracts quotes and their authors from the website https://quotes.toscrape.com/. The extracted data is stored in a Pandas DataFrame and then saved as a CSV file.

 Features
- Fetches webpage content using the requests library.
- Parses HTML using BeautifulSoup.
- Extracts:
  - Quote text
  - Author name
- Stores the data in a Pandas DataFrame.
- Saves the extracted data as quotes_dataset.csv.

 Technologies Used
- Python 3
- requests
- BeautifulSoup4
- pandas

 Installation

1. Clone the repository:

git clone <repository_url>

2. Navigate to the project folder:

cd <project_folder>


3. Install the required libraries:

pip install requests beautifulsoup4 pandas


 Usage

Run the Python script:


python scraper.py

Output

The script will:
- Display the first five rows of the dataset.
- Generate a CSV file named:

quotes_dataset.csv

Example Output:

| Quote | Author |
|--------|---------|
| "The world as we have created it..." | Albert Einstein |
| "It is our choices..." | J.K. Rowling |

 Project Structure

project/
│
├── scraper.py
├── quotes_dataset.csv
└── README.md


 Website Used

https://quotes.toscrape.com/

 Author

Maradugula Srija

License

This project is for educational purposes.
