# Sentiment-Analysis-and-NLP-Metrics-of-Web-Pages
Imports openpyxl, requests, BeautifulSoup, TextBlob, and nltk libraries.
Loads an XLSX file named "Input.xlsx" and gets the links from column B in the sheet named "Sheet1".
Loops through the links and uses BeautifulSoup to scrape the page's title and content.
Writes the content of each page to a separate text file with the title as the filename.
Installs TextBlob and downloads the necessary NLTK corpora.
Loop through all the text files and perform NLP analysis using TextBlob and cmudict.
Calculates various NLP metrics such as positive/negative scores, polarity etc.
