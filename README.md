# Analysis of Emirates customer reviews

**Objective:** Understand how customers feel about the Emirates brand.
<hr>

**Tasks:**
1. Scrape and collect customer feedback from the third-party website.
2. Conduct EDA and data cleaning.
3. Generate a word cloud from customer reviews.
4. Perform sentiment analysis.
<hr>

**Results:**
* The collected data includes 2345 Emirates customer reviews and covers the period from December 2013 to March 2024.
* A 1-star rating out of 10 is prevalent in the reviews.
<!--  -->
![WordCloud](pictures/distribution.png)

* Top-5 countries of review origin: UK, Australia, US, UAE, and Germany.
<!--  -->
![WordCloud](pictures/piechart.png)

* The frequency word cloud below shows that the key topics within the reviews include **service**, **seat**, **food**, and **staff**, showing that people are actively talking about their experience and staff.
<!--  -->
![WordCloud](pictures/wordcloud.png)

* Out of 2345 reviews, 1254 were positive, 904 were negative and 187 were neutral. This means the majority of reviews were polarised as either positive or negative.
<!--  -->
![PieChart](pictures/piechart2.png)
<hr>

**Libraries employed:**

`pandas` `requests` `beautifulsoup` `seaborn` `matplotlib` `plotly` `wordcloud` `nltk` `tqdm`
