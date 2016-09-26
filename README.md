# CFPB_complaints_public
Analysis using CFPB's public [Consumer Complaints Database](http://www.consumerfinance.gov/data-research/consumer-complaints/)

## Financial Companies Type
Creates dataset for classifying institution type into depository or non-depository, then sub-type within each.

Uses open data from FDIC and listings of payday lenders on various sites, as well as web scraping Wikipedia using Requests and BeautifulSoup.

## Complaints Analysis
* **Aggregates data** by companies, issue, tag, and product to compare complaints over time.
* Uses **visual analysis** to split data, see distributions and outliers, view trends over time.
* Uncovers relationships with correlation and regressions.
* Uses **NLP** to classify consumer complaint narratives and company responses.