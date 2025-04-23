# Rent the Runway – Exploratory Data Analysis (EDA)

## Overview
This project provides an in-depth exploratory data analysis (EDA) of the Rent the Runway dataset, which includes user reviews, product information, and user attributes. The analysis aims to uncover insights about customer behavior, product ratings, and review sentiment.


## Dataset
  Source: [Rent the Runway dataset](https://cseweb.ucsd.edu/~jmcauley/datasets.html#clothing_fit)
    
## Key Analysis Areas
1. User Behavior Analysis
    Identified rental frequency trends (long-tail distribution).
    Analyzed body type and age group preferences — core users are 26–35 year old.
    Found category preferences shift with age and body type.

2. Product Analysis
    Dresses and gowns dominate rentals; dresses receive higher satisfaction ratings.
    Category preferences vary by body type (e.g., athletic body types prefer A-line dresses).
    Common sizes: 8, 4, and 12.
    Fit feedback highlights sizing issues for specific item-body type combinations.

3. Fit Feedback Analysis
    Majority of items fit as expected (~70%).
    Specific categories (e.g., sheath and shift dresses) have higher fit complaints.
    Sentiment and rating patterns linked to fit satisfaction.

4. Time-Based Trends

    Clear seasonal patterns in rental occasions:  
   - Weddings peak May–September  
    - Formal affairs rise in November–January. 
    Dresses dominate Spring and Fall rentals.
    Year-over-year growth in specific categories.

5. Review Text & Sentiment Analysis

    Word clouds reveal common phrases like “perfect fit” and “tight.”
    Sentiment analysis confirms mostly positive reviews.
    Longer reviews correlate with extreme (high/low) ratings.

6. Customer Segmentation

    Segments identified by age, rental occasion, and frequency.
    26–35-year-olds are most loyal and frequent renters.
    High-value customers often rent for weddings and work events.

7. Occasion-Based Marketing Calendar

    Event-driven demand:
   - Weddings, formal affairs, and parties drive peak rentals.
   - Aligning inventory with seasonal demand can optimize performance.

8. Customer Retention Insights

    Repeat customers are key to growth, especially after 2015.
    Younger (15–25) and older (55+) users are more likely one-time renters.
    Rentals for weddings and work see the highest retention.


## Notebook Includes
- Data loading & cleaning
- Feature engineering (e.g., date formatting, sentiment scoring)
- 2D and 3D plots for deeper visual exploration
- Insights on how body type, height, and size influence product ratings
