# Goodreads-Data-Report

## 1.0 Introduction
[Kindly access my Tableau interactive dashboard here](https://public.tableau.com/app/profile/azeez.olasupo/viz/GoodreadsDashboard_17117128023500/GoodreadsDashboard)


![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/goodread.png)

In this comprehensive report, I present a detailed analysis and visualization project leveraging the Goodreads dataset from Kaggle. As a premier platform for book enthusiasts, Goodreads offers a treasure trove of data on books, authors, publishers, and reader ratings.

The primary objective of this project is to uncover key insights and trends within this rich dataset. Through the creation of interactive dashboards, I aim to provide a visually compelling and insightful overview of the literary landscape, empowering users to better understand the dynamics and performance indicators driving the world of books.

By meticulously analyzing and visualizing various KPIs, this report offers a deep dive into the data, revealing intriguing patterns, popular genres, influential authors, and more. Dive in and explore the captivating world of literature through the lens of the Goodreads community.


## 2.0 Problem Statement

_The primary objective of this project is to analyze the Goodreads dataset to extract meaningful insights and present them through intuitive visualizations. Specifically, I aim to address the following questions:_
- How has the publication of books evolved over time?
- Which authors have published the most books?
- Which publishers are the most prolific?
- What are the most common languages for books in the dataset?
- Which book titles have the highest rating counts?


## 3.0 Skills Demonstrated

_Through this project, I demonstrate my proficiency in:_
- Data extraction and preprocessing from a complex dataset.
- Utilizing Tableau to create interactive and insightful visualizations.
- Applying data visualization best practices to convey information effectively.
- Analyzing trends and patterns in literary data to draw actionable conclusions.
- Presenting technical findings in an accessible and understandable format.


## 4.0 Data Sourcing
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/data%20source.PNG)

The data for this project was sourced from Kaggle’s Goodreads dataset, which includes comprehensive information about books, such as titles, authors, publishers, publication dates, language codes, and rating counts. This dataset is publicly available and provides a rich resource for literary analysis.



## 5. Data Transformation and Modeling

![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/data%20modelling.PNG)

_To prepare the data for visualization, I performed the following steps:_
- Data Cleaning: Removed duplicates, corrected inconsistencies, and handled missing values.
- Normalization: Standardized author names, publisher names, and other categorical data to ensure consistency.
- Aggregation: Calculated total books by author, publisher, and language code.
- Derived Metrics: Created additional fields such as total books by publication date and rating count per title.

_The data was structured into several key tables:_
- Books: Including book titles, authors, publishers, publication dates, language codes, and rating counts.
- Authors: Aggregating data related to each author’s total number of books.
- Publishers: Aggregating data related to each publisher’s total number of books.
- Languages: Summarizing data on the most common language codes for books.
_**These models facilitated the creation of relationships and hierarchies necessary for the dashboards.**_

## 6.0 Analysis and Visualization

_Using Tableau, I created several interactive dashboards to display the key performance indicators:_

**_6.1 Books by Publication Date_**
---
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/Books%20by%20publication%20date.PNG)
_Purpose: To visualize the trend in the number of books published over time._
_Visualization: An area chart showing the total number of books published each year, highlighting peaks and trends over decades._

**_6.2 Authors by Total Books_**
---
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/Authors%20by%20total%20books.PNG)

_Purpose: To identify the most prolific authors in the dataset._
_Visualization: A horizontal bar chart displaying the top authors based on the total number of books published._

**_6.3 Publishers by Total Books_**
---
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/publishers%20by%20total%20books.PNG)

_Purpose: To recognize the most prolific publishers in the dataset._
_Visualization: A horizontal bar chart showing the top publishers by the number of books published._


**_6.4 Top 10 Language Codes_**
---
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/Top%2010%20Language%20codes.PNG)

_Purpose: To determine the most common languages in which books are published._
_Visualization: A radial chart illustrating the distribution of the top 10 language codes._

**_6.5 Titles by Rating Count_**
---
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/Titles%20by%20rating%20count.PNG)

_Purpose: To highlight the books with the highest engagement in terms of rating counts._
_Visualization: A horizontal bar chart showing the book titles with the highest number of ratings._

**_6.6 Final Dashboard displaying all KPIs in a glance_**
---
[Kindly access my interactive dashboard here](https://public.tableau.com/app/profile/azeez.olasupo/viz/GoodreadsDashboard_17117128023500/GoodreadsDashboard)
![](https://github.com/paragon-tech001/Goodreads-Data-Report/blob/main/Good%20reads%20Dashboard.png)

## 7.0 Conclusion and Recommendation

_The visualizations created from the Goodreads dataset provide valuable insights into the literary world. Key findings include_

1. **_Publication Trends:_** The area chart reveals significant trends in book publication over time, showing periods of increased literary output.
2. **_Prolific Authors:_** The horizontal bar chart identifies authors with the highest number of published books, highlighting their contribution to literature.
3. **_Prolific Publishers:_** Another horizontal bar chart shows the publishers with the most books, indicating their influence in the publishing industry.
4. **_Language Distribution:_** The radial chart provides a clear view of the most common languages for books, which can inform translation and market strategies.
5. **_Engagement Metrics:_** The horizontal bar chart on rating counts shows which books have garnered the most reader engagement, useful for marketing and promotional efforts.

---
   
_Recommendations based on these findings include:_

- **_Marketing Strategies:_** Focus promotional efforts on books and authors with high engagement metrics to maximize impact.
- **_Content Strategy:_** Invest in translations and publications in the most common languages to reach broader audiences.
- **_Historical Analysis:_** Use trends in publication dates to inform future publishing schedules and inventory planning.

---

**_This project demonstrates the power of data visualization in extracting meaningful insights from complex datasets, providing stakeholders with actionable information to make informed decisions in the literary industry._**

