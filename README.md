# AI Tools for Business in India (2025) – Google Trends Analysis

## Overview

This project analyzes the search behavior of Indian users towards **AI tools for business** using **Google Trends (2025)** data. The objective is to identify current business interests, emerging AI trends, brand awareness, and search momentum to understand how AI adoption is evolving in the Indian market.

The analysis was performed using **Power BI** for data preparation, visualization, and insight generation.

---

## Objectives

* Analyze the most searched AI-related business queries in India.
* Identify emerging AI trends using Google Trends' Rising Queries dataset.
* Categorize search queries based on business intent.
* Compare current search demand with emerging search momentum.
* Interpret periodical search interest throughout 2025.
* Generate business-oriented insights and recommendations.

---

## Dataset

The project uses two Google Trends datasets for India (2025):

### 1. Top Queries

Represents the AI-related business queries with the highest search interest.

Columns:

* Query
* Search Interest
* Increase %
* Intent Category (derived)

### 2. Rising Queries

Represents AI-related business queries experiencing the fastest growth in search interest.

Columns:

* Query
* Search Interest
* Increase %
* Intent Category (derived)

---

## Data Preparation

The datasets were cleaned in **Power BI Power Query** through the following steps:

* Removed irrelevant academic and certification-style queries.
* Removed examination-oriented multiple-choice questions.
* Corrected data types.
* Added an **Intent Category** column to classify queries into:

  * Tool Discovery
  * Brand Interest
  * Market / Industry Awareness
  * Future / Strategic AI

The analysis retained only business-relevant search queries.

---

## Dashboard Overview

### Page 1 – Current AI Demand in India

Focus:

* Most searched AI business queries
* Search interest distribution
* Business intent analysis

Visuals:

* Search Interest by Query
* Query Count by Intent Category
* Query Details Table
* Business Insight Summary

---

### Page 2 – Rising AI Trends

Focus:

* Fastest-growing AI business queries
* Emerging market interest
* Trend comparison

Visuals:

* Rising Queries Table
* Query Count by Intent Category
* Trend Insight Summary

---

## Periodical Trend Analysis

Google Trends periodical search interest (Dec 2024 – Jan 2026) was analyzed separately and divided into three phases:

### Phase 1

**December 29, 2024 – June 1, 2025**

* Search interest remained relatively low (9–15).
* One temporary drop to 0 occurred on April 13, 2025.
* Indicates early exploration and limited business adoption.

### Phase 2

**June 1 – October 26, 2025**

* Search interest reached 50 on June 15, 2025.
* Interest declined afterward and stabilized around 20.
* Lowest value during this phase was 5 on October 5, 2025.
* Represents transition from initial excitement to practical evaluation.

### Phase 3

**October 27, 2025 – January 4, 2026**

* Strong upward momentum throughout November.
* Peak search interest reached 100 on December 7, 2025.
* Interest declined to 43 by January 4, 2026.
* Indicates widespread business attention followed by market normalization.

---

## Key Findings

* Businesses primarily searched for affordable and effective AI tools.
* Brand-specific searches indicate strong interest in platforms such as Gemini, Perplexity, and Jasper.
* Tool discovery remains a dominant search intent.
* AI-related news generated significant attention during peak periods before stabilizing.
* Rising queries suggest that businesses are moving from general awareness toward evaluation and selective adoption of AI solutions.

---

## Tools Used

* Power BI
* Power Query
* Google Trends

---

## Project Structure

```
AI-Tools-for-Business-India-2025/
│
├── Data/
│   ├── AI_tools_top_queries_India_2025.csv
│   └── AI_tools_trends_India_2025.csv
│
├── PowerBI/
│   └── AI_Tools_for_Business_India_2025.pbix
│
├── Images/
│   ├── Dashboard_Page1.png
│   └── Dashboard_Page2.png
│
└── README.md
```

---

## Limitations

* Google Trends provides relative search interest rather than absolute search volume.
* "Breakout" values represent exceptional growth and were treated qualitatively rather than converted into numeric percentages.
* Historical timeline values from Google Trends were available only as visual charts and were interpreted qualitatively for the periodical trend analysis.

---

## Conclusion

The analysis indicates that AI adoption among Indian businesses progressed through distinct phases during 2025, beginning with exploratory interest, followed by market evaluation, and culminating in a significant surge in late 2025. Search behavior suggests increasing business focus on practical AI tools, trusted AI brands, and long-term adoption strategies rather than experimental exploration.
