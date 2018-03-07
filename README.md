# Yellow Pages Business Details Scraper

Yellowpages.com Web Scraper written in Python and LXML to extract business details available based on a particular category and location.

If you would like to know more about this scraper you can check it out at the blog post 'How to Scrape Business Details from Yellow Pages using Python and LXML' - https://www.scrapehero.com/how-to-scrape-business-details-from-yellowpages-com-using-python-and-lxml/

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Fields to Extract

This yellow pages scraper can extract the fields below:

1. Rank
2. Business Name
3. Phone Number
4. Business Page
5. Category
6. Website
7. Rating
8. Street name
9. Locality
10. Region
11. Zipcode
12. URL

### Prerequisites

For this web scraping tutorial using Python 3, we will need some packages for downloading and parsing the HTML. 
Below are the package requirements:

 - lxml
 - requests

### Installation

PIP to install the following packages in Python (https://pip.pypa.io/en/stable/installing/) 

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/)

Python LXML, for parsing the HTML Tree Structure using Xpaths (Learn how to install that here – http://lxml.de/installation.html)

## Running the scraper
We would execute the code with the script name followed by the positional arguments **keyword** and **place**. Here is an example
to find the business details for restaurants in Boston. MA.

```
python3 yellow_pages.py restaurants Boston,MA
```
## Sample Output

This will create a csv file:

[Sample Output](https://raw.githubusercontent.com/scrapehero/yellow_pages/master/restaurants-boston-yellowpages-scraped-data.csv)
 
 
