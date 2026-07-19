# Indian Startup Funding Analysis Dashboard

## Project Overview
This project analyzes real-world data on Indian startup funding (2015-2020) to uncover 
patterns in investment activity across cities, industries, and time. It was developed 
as a final internship project focused on data-driven decision-making — transforming a 
raw dataset into a clean, interactive visual format using Tableau Public.

## What I Did
1. **Data Cleaning** — Cleaned the raw Kaggle "Indian Startup Funding" dataset using 
   Python (Pandas) in Google Colab: fixed inconsistent date formats, converted funding 
   amounts from text to numeric values, standardized city names (merging spelling 
   variants), and grouped 500+ messy industry labels into clean, broad categories.
2. **Dashboard Development** — Built an interactive dashboard in Tableau Public featuring:
   - A map showing funding distribution by city
   - A bar chart showing startup share by industry category
   - A line graph showing funding trends by year
   - KPI summaries (total funding, total deals, top city)
3. **Documentation** — Prepared a concept note and final presentation explaining the 
   project's objective, data description, KPIs, and key insights.

## Live Dashboard
https://public.tableau.com/authoring/Indian_Startup_Funding_Dashboard/Dashboard2#1

## Repository Contents
- `startup_funding_cleaned.csv` — cleaned dataset
- `data_cleaning.ipynb` — Google Colab notebook with all data cleaning steps
- `Concept_Note.pdf` — Project concept note
- `Final_Presentation.pptx` — final presentation slides

## Key Insights
Key Insights

E-Commerce/Marketplace dominates Indian startup funding, attracting the highest total investment at ₹1,100+ crore ($11B), ahead of Technology/SaaS ($5B) and FinTech ($3.7B) — signaling investor confidence in India's digital retail boom.
SoftBank is the single largest investor, contributing $2.5B individually and appearing again via "SoftBank Group" ($1.46B) — together accounting for nearly 12% of total funding tracked, highlighting how concentrated mega-investors shape the ecosystem.
Funding activity is highly volatile year-over-year, swinging from a low of $390M to a peak of $10.4B — rather than steady growth, Indian startup funding moves in sharp cycles likely tied to a small number of massive individual rounds.
A total of $32.9 billion was raised across 2,138 funded startups, with funding concentrated in major hubs (visible in the city map) — reinforcing that investment is geographically concentrated rather than evenly spread across India.
The "Other" category still holds significant funding ($7.2B), indicating a long tail of niche/hybrid startups that don't fit neatly into standard industry buckets — worth noting as both a data limitation and a real reflection of India's diverse startup landscape.

## Tools Used
Python (Pandas), Google Colab, Tableau Public
