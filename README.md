# Kickstarter Campaign Analysis Using Excel

## Overview of Project

This project uses data about Kickstarter campaigns to analyze what factors may lead to launching a successful campaign by use of Microsoft Excel data visualizations and descriptive statistics formulas.

### Purpose

Kickstarter campaigns were analyzed specifically in the theater category to determine the viability of a campaign launched in that domain and draw potential conclusions on what can influence the outcome of a campaign. Of particular interest are play productions that take place in the United States.

## Analysis and Challenges

First the data was analyzed via filtering the columns of the spreadsheet to ensure completeness; the dates provided where encoded as Unix timestamps and needed conversion to actual dates for actual analysis. Theater/plays as a total category was also divided into a parent category and subcategory to allow for ease of filtering.

A separate sheet was used to use built-in Excel Function to summarize the data by examining some measures of central tendencies, spread and standard deviation. The data was filtered to only examine campaigns taking place in the US within the plays subcategory and is summurized by the following table:

| &nbsp; | Successful | Failed |
| --- | --- | --- |
| Mean goal | $5,049 | $10,554 |
| Median Goal | $3,000 | $5,000 |
| STDEV of Goal | $7,749 | $21,968 |
| UQ of Goal | $5,000 | $10,000 |
| LQ of Goal | $1,500 | $2,000 |
| IQR of Goal | $3,500 | $8,000 |
|  &nbsp; | Successful | Failed |
| Mean Pledged | $5,602 | $559 |
| Median Pledged | $3,168 | $103 |
| STDEV Pledged | $8,335 | $1,331 |
| UQ Pledged | $5,699 | $501 |
| LQ Pledged | $1,717 | $9 |
| IQR Pledged | $3,982 | $492 |

The impact of the date when a campaign is launched may have on the outcome of a campaign in the theater parent category was also investigated. To visualize this dataset better, the count successful, failed, or canceled outcomes were plotted against each month of the year; ongoing campaigns were no conclusive outcome can be determined were omitted from the dataset.

![Chart of Outcomes vs. Launch Date](/resources/Theater_Outcomes_vs_Launch.png)

Lastly data for the plays subcategory was broken down into brackets based on the campaign's desired goal to find the percentage of projects that were successful, failed or canceled in each bracket. Brackets were broken into increments of $5,000 except for the lower $1,000 and anything over $50,000. A line chart visualizing the percentages of each outcome plotted vs. the goal bracket was produced.

![Chart of Outcomes vs. Goals](/resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Launch Date



### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
