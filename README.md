# Shopify App Marketplace Performance Analysis

**Tools:** Power BI · DAX · Data Modeling · Dashboard Development

## Overview

The Shopify app marketplace lists thousands of apps, and merchants choosing between them rely on ratings and reviews that are hard to compare at a glance. This project analyzes **7,342 Shopify apps** and **640,634 reviews** in Power BI to evaluate marketplace trends, review activity, and ratings — and to identify the factors associated with strong app performance, including how helpful an app's reviews are and how responsive its developer is.

## What I built

- A 3-page Power BI report: **App Landscape**, **Reviews**, and **App Reviews**
- **DAX metrics** assessing review helpfulness (`helpful_reviews = rating * (1 + helpful_count)`) and developer responsiveness (`developer_answered = 1` when the developer replied), so quality signals go beyond a raw star rating
- Comparative views that surface patterns in ratings and engagement to support app evaluation and marketplace decisions

## Key findings

- Star ratings barely separate apps: once an app has meaningful review volume, ratings converge tightly toward 4.5–5 — the median 4.8-star app has just 3 reviews, so review depth matters more than the stars
- Review activity concentrates on a subset of apps, so most listings compete with relatively little social proof — a visibility problem as much as a quality one
- The responsiveness metrics give merchants a practical shortlisting signal: apps whose developers engage with reviews tend to present a measurably different ratings profile

## Data

Public data scraped from the Shopify App Store (`shopify.xlsx`, 93.5 MB — too large to commit here; [download the dataset](https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/BIA/Dataset/shopify.xlsx)):

- `apps` — 7,342 apps with details, ratings, and review counts
- `reviews` — 640,634 user reviews with ratings, comments, and developer responses
- `apps_categories` — 10,165 app–category links
- `categories` — 10 categories

## Repository contents

- `README.md` — this overview and the documented findings
- `Power-BI-Project-Submission.pdf` — the full submitted report (8 pages)
- `screenshots/` — the 8 dashboard screenshots from the report, one per analysis question

## Links

- More projects: [github.com/fawariclement-lab](https://github.com/fawariclement-lab)
- LinkedIn: [linkedin.com/in/clement-fawari](https://www.linkedin.com/in/clement-fawari)
- Tableau Public: [public.tableau.com/app/profile/clement.fawari](https://public.tableau.com/app/profile/clement.fawari)

---

By **Clement Fawari** — Business Intelligence & Data Analyst, founder of **Consult 5.0** (BI dashboards, data analytics, and reporting for small businesses, online brands, and vacation-rental owners).
