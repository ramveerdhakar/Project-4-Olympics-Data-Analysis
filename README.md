## Olympics Data Analysis

This project uses a Summer Olympics medals dataset containing all medal winners from the 1976 Montreal Games to the 2008 Beijing Games, covering every awarded medal in that period.  The data is suitable for beginners to practice **data** analysis, advanced Excel, Python analytics, and introductory machine learning on sports performance.

### Dataset Description

- **Domain**: Sports analytics / Olympic medals.
- **Scope**: All medal winners in Summer Olympics (1976–2008).
- **Source**: Structured CSV of medal results for each athlete-event combination.

Main columns used for analysis:  
- `City`: Host city of the Olympic Games.
- `Year`: Year of the Olympics.
- `Sport`: Main sport category (e.g., Athletics, Swimming).
- `Discipline`: Subcategory within a sport.
- `Event`: Specific event (e.g., 100m, 3m springboard).
- `Athlete`: Athlete name.
- `Gender`: Athlete gender.
- `CountryCode`: Country abbreviation.
- `Country`: Full country name.
- `Eventgender`: Gender category of the event.
- `Medal`: Type of medal (Gold, Silver, Bronze).

The dataset supports medal distribution analysis by country, athlete, sport, gender, and time, and can be extended to predictive modeling tasks.

***

## Problem Statement

Understanding which countries, sports, and athletes dominate the Olympics over time helps reveal performance trends, investment impact, and equity in participation.  This dataset of Summer Olympics medal winners from 1976 to 2008 provides detailed information on every medal, enabling analysis across countries, events, and gender.

The main problem is to analyze how medals are distributed over years, countries, sports, and genders, identify top-performing countries and athletes, and examine participation gaps between male and female events.  Additionally, the project explores whether simple machine learning models can predict medal-winning likelihood based on features such as country, sport, and gender.

***

## Tasks

- Load and clean the Olympics medals dataset (fix data types, drop unused columns, and handle missing values).
- Perform exploratory analysis of total medal counts by country, year, sport, and athlete.
- Analyze gender distribution in events and medals to understand participation and success gaps.
- Visualize key insights with plots (top countries, medal trends over years, top athletes, and sport dominance).

