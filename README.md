# README for Module 11 Challenge (webscrape-challenge)

## Introduction

This challenge involves web scraping, specifically scraping titles, preview text, and tables. The content is about the planet Mars: news and data about the red planet.

## Data

The data comes from two Mars websites. Both the table and the news are in HTML format.

## Methodology

This challenge uses Splinter and Beautiful Soup libraries to help scrape the HTML text from the websites. First Splinter is used to automate browsing to the site, and Beautiful Soup is then used to the extract the HTML code from the site. Eventually Pandas and Matplotlib are used to query and plot some of the scraped data. Pandas is used to create a DataFrame and export it to a CSV file.

## Results and Conclusion

The web scraping provided a relatively easy way to extract HTML data from websites and allow for Pandas to query the data.  The data itself was no remarkable per se although, the plots of average minimum temperature show that Mars is a cold planet. Mars also has very long years compared to Earth.

## References

Class materials were used extensively for this assignment, as well as:

* stackoverflow.com
* Xpert Learning Assistant
* ChatGPT.com

## Usage

The CSV file was exported to the same directory as the two IPYNB files. All relevant materials are stored within the <mars_scrape> directory (aside from this README file).
