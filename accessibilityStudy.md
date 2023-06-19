---
layout: page-with-section
title: Accessibility Study
description: 
---
## Large Scale Accessibility Study

In this project we will conduct a large-scale scrapping of the web. We will access the top 1 million most accessed websites according to the DomCop Top 10 million domains (https://www.domcop.com/top-10-million-domains).

For each website we will extract: 

1. Information regarding what types of technologies/frameworks/libraries were used for its development, using the open-source library Wappalyzer (https://github.com/wappalyzer/wappalyzer); 

2. Accessibility barriers found using the open-source library AXE core (https://github.com/dequelabs/axe-core); 

3. The raw html, external javascript and css script references, image links and their alt text, cookies and Javascript and CSS coverage metrics.

To ensure that the web scrapping is conducted ethically we will ensure that: 

1. Data will be scraped at a reasonable rate and we will throttle the number of requests per second, this way avoiding the website owner to think he is being a victim of a DDoS attack; 

2. We will ensure that we will not scrape private data, we will first analyse the domain 'robots.txt' file to ensure which URLs are we allowed to scrape by the website owner(http://www.robotstxt.org/robotstxt.html);

3. We will ensure our scrapper has a user agent string, making us identifiable to website owner.

This data will later be analysed at an aggregate level to find a relation between the technologies found and the accessibility barriers reported by the tool. We will also conduct a sample based approach to analysing the data, where we will select specific sets of data to examine manually.

All data will be anonymised for external publication of papers, website dissemination and organisations as expressed in the study’s research agreement and according to University rules.

For more information contact me at [luis.a.carvalho@northumbria.ac.uk](mailto://luis.a.carvalho@northumbria.ac.uk)
