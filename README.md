# Netflix Data Analysis using SQL

A SQL-based data analysis project on the **Netflix Movies and TV Shows dataset** — exploring content trends, genre distributions, country-wise production, and release patterns using structured queries.

---

## Project overview

This project uses SQL to answer real business questions about Netflix's content library. The analysis covers content type distribution, top-producing countries, genre trends, director/cast frequency, and content addition patterns over the years.

---

## Dataset

- Source: Netflix Movies and TV Shows dataset (publicly available on Kaggle)
- Contains: ~8,000+ titles including movies and TV shows
- Fields: title, type, director, cast, country, date_added, release_year, rating, duration, genres

---

## Questions answered

```sql
-- Sample questions explored:
-- 1. What is the ratio of Movies vs TV Shows on Netflix?
-- 2. Which country produces the most Netflix content?
-- 3. What are the top 10 most common genres?
-- 4. Which directors have the most titles on Netflix?
-- 5. How has Netflix content grown year over year?
-- 6. What ratings (PG, R, TV-MA) are most common?
-- 7. Which year had the most content added?
-- 8. What is the average duration of movies by genre?
```

---

## Tech stack

| Tool | Purpose |
|------|---------|
| SQL (PostgreSQL / MySQL) | All analysis queries |
| CSV dataset | Raw data source |

---

## Project structure

```
Netflix-Data-Analysis-using-SQL-project/
├── Netflix Data Analysis using SQL project/
│   ├── netflix_titles.csv     # Dataset
│   ├── analysis_queries.sql   # All SQL queries
│   └── schema.sql             # Table creation script
└── README.md
```

---

## Key SQL concepts used

- `GROUP BY` with aggregations (`COUNT`, `AVG`, `MAX`)
- `CASE WHEN` for conditional categorisation
- `RANK()` and `ROW_NUMBER()` window functions
- `DATE_PART` / `EXTRACT` for year-based analysis
- String functions for genre parsing
- Subqueries and CTEs

---

## What I learned

- Writing complex analytical SQL queries on a real-world dataset
- Using window functions for ranking and partitioning
- Structuring a SQL analysis project end-to-end
- Translating business questions into SQL queries

---

## Author

**Arish Mahammad** · [@rIS-spec](https://github.com/rIS-spec)
