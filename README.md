# HN Top Stories Email Automation
A simple Python script to extract the top news stories from Hacker News and send them as an email. The script uses the requests library to fetch the website content and BeautifulSoup to extract the news stories. The email is sent using the smtplib library and the email content is in HTML format.

## Requirements
- Python 3
- requests
- BeautifulSoup
- smtplib

## Installation
```python
pip install requests
pip install beautifulsoup4
```

## Usage
- Replace the sender and receiver email ids and password in the script.
- Run the script:
```
python hn_email.py
```
