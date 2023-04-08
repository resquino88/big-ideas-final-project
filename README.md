# Big Ideas Final Project (Final Project Group 47)

## Team Members
- Ryan Esquino: rne7@pitt.edu, convenience_stores.ipynb
...

## Datasets Used
- convenience_stores.ipynb: https://data.wprdc.org/dataset/allegheny-county-restaurant-food-facility-inspection-violations/resource/112a3821-334d-4f3f-ab40-4de1220b1a0a
> Provides data about food facilities in the area for each municipal. Data used in the notebooks graphs is filtered by the description.
...

## Overview
> This repository looks to find the best area for Homer Simpson to live in based on the following categories: number of donut shops (50% weight), bars (40% weight), and convenience stores (10% weight) in each area. The best area is determined based on the lowest sum of each ranking of an area in the specific category times its weight. If the number of donut shops, for example, in Moon township is ranked second, bars third, and convenience stores sixth, then Moon's overall score would equal: (2 * 0.5) + (3 * 0.4) + (6 * 0.1) = 2.8.