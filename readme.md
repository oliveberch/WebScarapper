# Web Scrapper

## Overview
This project aims to scrape email addresses from a specified website and store them in a CSV file.

## Usage Instructions
1. **Install the required libraries:**
   ```
   pip install requests beautifulsoup4
   ````
2. Open the web_scraping_project.ipynb file in a Jupyter Notebook environment.

3. Customize the target_url variable:

- In the Jupyter Notebook, locate the cell containing the code.
- Find the line target_url = 'https://example.com'.
- Replace 'https://example.com' with the URL of the website you want to scrape.

4. Run the cells sequentially:

- Execute each cell in order to run the web scraping process.
- Review the output and any error messages.

5. Check the results:

- The scraped email addresses will be stored in a CSV file named scraped_emails.csv in the same directory.

## File Structure
- web_scraping_project.ipynb: Jupyter Notebook file containing the code.
- scraped_emails.csv: CSV file where the scraped email addresses are stored.

## Dependencies
- requests: Library for making HTTP requests.
- beautifulsoup4: Library for pulling data out of HTML and XML files.

## Issues and Contributions
If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.