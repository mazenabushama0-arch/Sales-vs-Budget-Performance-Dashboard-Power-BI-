# Sales vs Budget Performance Dashboard (Power BI)

> 🌐 Part of my data analytics portfolio: [My-PORTFOLIO](https://mazenabushama0-arch.github.io/Portfolio/) · 👤 [More projects on my GitHub](https://github.com/mazenabushama0-arch)

A 4-page Power BI report that tracks **sales against budget for 2016**, explains where the gap comes from, and projects where sales are heading. It moves from a high-level executive view, to monthly performance, to diagnostics by category and region, and ends with a forward-looking outlook.

**Full preview:** [`Final_Project.pdf`](Final Project.pdf)

> Final project for the Diploma in Data Analysis & AI Applications (Institute of Management Professionals).

---

## Business questions

- Did sales reach the budget, and by how much did they miss or beat it?
- Which product lines, categories, and regions drive sales and profit?
- In which months does performance fall short of budget?
- Which categories and regions explain the budget variance?
- If the current trend continues, what sales should we expect, and what monthly sales are needed to close the gap?

## Dashboard pages

| Page | What it shows |
|---|---|
| **Executive Performance Overview** | Total sales, sales growth, budget achievement %, profit, and margin %; sales by product line, region, and category; sales vs budget by month; sales vs last year by month; an auto-generated insight on the best month |
| **Monthly Performance Analysis** | Total sales, total budget, budget achievement %, budget variance, and profit; sales vs budget by month; monthly budget variance waterfall; month × category matrix; sales by region, switchable by category or region |
| **Diagnostic Analysis** | Decomposition tree of budget variance by category and region; budget variance by region; region × category matrix; sales by month and category; budget achievement %, profit, and sales by category |
| **Future Outlook** | Projected sales, gap to target, and required monthly sales; sales forecast with confidence band into 2017; what-if parameter; sales vs last year vs projected sales by month; sales, projected sales, and budget by category |

## Key results (2016)

- Total sales of **16.47M** against a budget of **16.87M**: **98% budget achievement** and a variance of **-395.96K**
- **Profit of 6.81M** at a **41.37% margin**
- **Bikes** make up about **94%** of sales; **Mountain** and **Road** are the top product lines
- **Australia** is the largest region, followed by Southwest and the United Kingdom
- **December** is the strongest month, with sales of about 1.95M

## Features

- Page navigation buttons and slicers for year, month, group, category, and region
- Field parameters to switch visuals between category, region, and sub-category
- Decomposition tree for root-cause analysis of budget variance
- Waterfall chart for monthly variance
- Forecast with a confidence interval, plus a what-if parameter for projected sales
- Smart narrative that explains the highest sales month

## Key measures (DAX)

`Total Sales` · `Total Budget` · `Budget Achievement %` · `Budget Variance` · `Profit` · `Margin %` · `Sales LY` · `Sales Growth` · `Projected Sales` · `Gap To Target` · `Required Monthly Sales`

## Tech stack

- Power BI Desktop
- DAX measures, field parameters, and what-if parameters

<!-- Add screenshots to an /images folder, then uncomment:
## Screenshots
![Executive Performance Overview](images/01-executive-overview.png)
![Monthly Performance Analysis](images/02-monthly-performance.png)
![Diagnostic Analysis](images/03-diagnostic-analysis.png)
![Future Outlook](images/04-future-outlook.png)
-->

## Author

**Mazen Mohsen**
Senior Data & Merchandise Analyst
[LinkedIn](https://linkedin.com/in/mazen-abushama-934246398)
