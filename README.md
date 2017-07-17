# README #

Code of a scrapy crawler that collects data from

https://www.theknot.com/marketplace/wedding-photographers-*

In two areas:

- New York, NY
- Los Angeles, CA

### Dependencies ###

This crawler is tested to work under Python 2.7.

Required dependencies to make this package run are:

lxml==3.7.3 package

You can install this dependent package with the following command:

pip install lxml

### Execution ###

You can run this scrapy crawler typing:

scrapy crawl amazonjobs -o file.csv -t csv

The previous command will output to a *.csv file

### Settings ###

This crawler is configured to cache pages for 24 hours. You can change
this behaviour by editing the 89 line in settings file:

weddingphoto/weddingphot/settings.py

Or disable caching by adding a # in the start of the line.

### Contact ###

Author: Luis Torres

* luis.e.torreslopez [at] gmail.com
* github.com/letorres
