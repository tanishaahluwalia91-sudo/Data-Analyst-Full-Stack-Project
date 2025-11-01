# Data-Analyst-Full-Stack-Project
Advance Excel, MySQL &amp; Power BI

---

# Netflix Content Analysis — Data-Driven Insights Dashboard

## Project Overview

This project analyzes the Netflix Titles dataset to uncover insights about content trends, genres, countries, and audience ratings.
Using SQL, Power BI, and Advanced Excel, the goal is to identify patterns in Netflix’s catalog and provide data-backed recommendations for content strategy and audience engagement.

---

## Objective

To analyze and visualize Netflix’s global content distribution and growth to answer key business questions such as:

* What type of content dominates Netflix — Movies or TV Shows?
* Which countries contribute the most titles?
* What are the most common genres and ratings?
* How has Netflix’s content evolved over time?

---

## Dataset Overview

| Column Name  | Description                          |
| ------------ | ------------------------------------ |
| show_id      | Unique identifier for each title     |
| type         | Movie or TV Show                     |
| title        | Name of the title                    |
| director     | Director of the title                |
| cast         | Main actors involved                 |
| country      | Country of production                |
| date_added   | Date when added to Netflix           |
| release_year | Original release year                |
| rating       | Audience rating (e.g., PG-13, TV-MA) |
| duration     | Duration (minutes or seasons)        |
| listed_in    | Genre or category                    |
| description  | Short summary of the title           |

---

## Data Cleaning and Preparation

Performed using SQL (MySQL) and Power Query in Power BI:

* Removed duplicates and handled missing values in `director`, `cast`, and `country`.
* Converted `date_added` to proper date format.
* Extracted numeric duration values for movies and seasons for TV shows.
* Split multi-valued columns such as `country`, `listed_in`, and `cast` into separate rows for better aggregation.
* Standardized text casing and category names.

---

## Exploratory Analysis (SQL)

# SQL Questions:

* How many total titles are available on Netflix?

* What percentage of content is Movies vs TV Shows?

* Which country produces the most Netflix content?

* Who are the top 10 most featured directors?

* What’s the most common rating (PG, TV-MA, R, etc.) by region?

* Which year saw the highest number of releases?

* What is the trend of Netflix releases over time (2008–2025)?

* What are the top 10 actors who appear in the most titles?

* How many titles belong to each genre/category (listed_in)?

* Which genres are most popular in each country?

* What is the average duration of movies vs. number of seasons for shows?

* Which countries dominate Netflix Originals (if mentioned in title or description)?

* How many titles were added each month/year (date_added trend)?

* What is the most common combination of genre + rating?

* What percentage of total content is from the top 5 countries?
---

## Key Performance Indicators (KPIs)

| KPI                | Description                                           | Business Use                           |
| ------------------ | ----------------------------------------------------- | -------------------------------------- |
| Total Titles       | Total number of titles available                      | Measures catalog size                  |
| Content Type Split | Percentage of Movies vs TV Shows                      | Identifies focus area                  |
| Top Countries      | Number of titles by country                           | Measures regional contribution         |
| Top Genres         | Most frequent genres                                  | Reveals audience preference            |
| Yearly Additions   | Titles added per year                                 | Tracks content growth                  |
| Common Ratings     | Distribution of audience ratings                      | Defines maturity level focus           |
| Average Duration   | Average runtime of movies or average seasons per show | Helps understand content format trends |

---

## Power BI Dashboard Structure

### Page 1: Overview

* KPI Cards: Total Titles, Content Split, Top Country, Top Genre
* Bar Chart: Movies vs TV Shows
* Line Chart: Titles added by year
* Map: Content distribution by country
* Slicers: Year, Country, Genre

### Page 2: Content Insights

* Heatmap: Genre vs Rating
* Bar Chart: Top Directors and Actors
* Gauge: Average Duration
* Word Cloud: Description keywords

### Page 3: Regional Analysis

* Treemap: Genres by Country
* Table: Top Genres per Region

### Page 4: Trends and Recommendations

* Line Chart: Yearly growth pattern
* Summary: Business insights and strategic recommendations

---

## Excel Analysis

Developed using Pivot Tables, Slicers, and Charts:

* Movie vs Show count by country
* Rating distribution by year
* Top 10 genres by frequency
* Monthly additions trend

Calculated metrics include:

* Year-over-year growth rate
* CAGR (Compound Annual Growth Rate) for yearly additions
* Percentage contribution of top 5 countries

---

## Key Insights

* Approximately 70% of Netflix’s catalog consists of Movies.
* The United States, India, and the United Kingdom produce the highest number of titles.
* Documentaries and International Dramas have grown significantly since 2018.
* TV-MA is the most common rating, indicating a focus on mature audiences.
* Regional and multilingual content has shown strong growth in recent years.

---

## Tools and Technologies

| Tool            | Purpose                                              |
| --------------- | ---------------------------------------------------- |
| SQL (MySQL)     | Data cleaning, transformation, and exploration       |
| Power BI        | Interactive dashboard and visualization              |
| Microsoft Excel | Data validation, pivot analysis, and KPI computation |
| Power Query     | Data preprocessing and normalization                 |
| DAX             | Custom calculations in Power BI                      |

---

## Project Structure

```
Netflix-Content-Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── sql/
│   └── netflix_analysis_queries.sql
│
├── powerbi/
│   └── netflix_dashboard.pbix
│
├── excel/
│   └── netflix_analysis.xlsx
│
├── README.md
│
└── insights/
    └── key_findings.pdf
```

---

## Business Recommendations

* Increase investment in regional dramas and documentaries, which show consistent growth.
* Focus on partnerships in India and South Korea, two rapidly expanding content markets.
* Maintain a balanced ratio of Movies to TV Shows to diversify audience reach.
* Continue producing mature content under TV-MA and PG-13 ratings, aligning with audience demand.

---

## Outcomes

* Developed a complete end-to-end data analytics project using SQL, Excel, and Power BI.
* Created a visually rich and KPI-driven dashboard.
* Delivered actionable business insights for strategic decision-making.
* Produced a portfolio-ready project demonstrating analytical thinking and technical expertise.

---

## Contact

**Author:** Tanisha Ahluwalia
**LinkedIn:** (https://www.linkedin.com/in/tanisha-ahluwalia/)
**Email:** [tanishaahluwalia91@gmail.com]
