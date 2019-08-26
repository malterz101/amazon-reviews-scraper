This is a simple Amazon Review scraper.

Anyone with Anaconda and Jupyter can run this automatically.

In it's current state it requires no installs beyond that included with conda.
I'll add a requirements.txt when I add more functionality to this.

This uses a combination of bs4, requests and regex and not much else. The output is a dictionary with all products from the first
page of results for a user search on Amazon. Each product includes top reviews with the text and rating.

I plan to add:

Export to CSV
Choose products to scrape
Amazon search result pagination
Sentiment Analysis

This is just the first draft, lots more coming as I build this up. 

Checkout my website maltby.io for my contact details.
