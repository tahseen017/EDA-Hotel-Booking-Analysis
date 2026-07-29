# 🏨 Hotel Booking Demand - Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.5+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)

## 📋 Project Overview

An in-depth exploratory data analysis of **119,390 hotel bookings** from two hotel 
types (City Hotel and Resort Hotel) spanning July 2015 to August 2017. This project 
demonstrates end-to-end data analysis: from messy raw data to actionable business insights.

**Business Problem**: Hotel cancellations cost the industry billions annually. 
Understanding WHY customers cancel and WHEN bookings peak can help hotels optimize 
pricing, staffing, and overbooking strategies.

---

## 🎯 Key Questions Answered

| # | Question | Finding |
|---|----------|---------|
| 1 | What is the overall cancellation rate? | **37.1%** of all bookings are canceled |
| 2 | Which hotel type has higher cancellations? | City Hotels (41.7%) vs Resort Hotels (27.9%) |
| 3 | When is peak booking season? | July-August for Resort, May/October for City |
| 4 | Where do most customers come from? | Portugal (home market) dominates, followed by UK, France |
| 5 | Does lead time affect cancellations? | Yes - bookings 365+ days in advance cancel at **60%** rate |
| 6 | Do returning guests cancel less? | Yes - new guests cancel **4x more** than returning guests |

---

## 📊 Key Visualizations

### Executive Dashboard
![Dashboard](reports/figures/08_executive_dashboard.png)

### Cancellation Analysis
![Cancellations](reports/figures/02_cancellation_by_hotel.png)

### Seasonal Trends
![Seasonality](reports/figures/03_monthly_seasonality.png)

---

## 💡 Business Recommendations

1. **Implement flexible cancellation fee tiers based on lead time** - bookings made 
   more than 90 days in advance should have stronger cancellation policies.

2. **Focus loyalty programs to convert new guests to returning guests** - returning 
   guests have a dramatically lower cancellation rate (6% vs 42%).

3. **City Hotels need dynamic overbooking strategies in May and October** - peak 
   months with high cancellation risk require buffer bookings.

4. **Resort Hotels can command 15-20% premium ADR in July-August** - data confirms 
   strong seasonal demand that supports premium pricing.

---

## 🗂️ Repository Structure