# Delhi Metro Network Analysis and Optimization 

## Overview
This project analyzes the Delhi Metro network using a structured dataset containing information about metro routes, schedules, stops, and trip frequencies. The objective is to gain insights into service patterns, connectivity, and optimization opportunities for reducing overcrowding and improving operational efficiency.

## Dataset Description 
The dataset consists of multiple files detailing various aspects of the Delhi Metro system:

- **Agency**: Information about Delhi Metro Rail Corporation (DMRC), including contact details.
- **Calendar**: Defines the operation days of metro services.
- **Routes**: Contains route names, descriptions, and classifications.
- **Shapes**: Provides geographical paths of metro lines using latitude-longitude coordinates.
- **Stop Times**: Timetables detailing arrival and departure times for each trip at different stops.
- **Stops**: Locations of metro stations with latitude-longitude data.
- **Trips**: Links trips to routes, with unique trip identifiers.

## Key Analyses and Insights 

### 1. **Geographical Paths of Metro Routes**
- Visualized metro routes on a map to understand network coverage.
- Each metro line was color-coded for clarity.

### 2. **Trip Frequency Analysis by Weekday**
- Merged `trips` and `calendar` datasets to analyze the number of trips per day.
- Found that weekday trips remain stable, while weekends show reduced services.

### 3. **Distribution and Connectivity of Stops**
- Mapped metro stops geographically to evaluate spatial distribution.
- Identified high-density zones and key transfer points.

### 4. **Route Complexity Analysis**
- Counted the number of metro routes passing through each stop.
- Highlighted major transfer hubs where multiple lines intersect.

### 5. **Service Frequency Analysis**
- Calculated time intervals between metro arrivals at each stop.
- Analyzed peak and off-peak travel times to detect congestion patterns.

### 6. **Trips and Capacity Analysis by Time Interval**
- Categorized trips into time intervals:
  - Early Morning (Before 6 AM)
  - Morning Peak (6 AM - 10 AM)
  - Midday (10 AM - 4 PM)
  - Evening Peak (4 PM - 8 PM)
  - Late Evening (After 8 PM)
- Observed high frequency during peak hours and lower frequency during late hours.

### 7. **Optimizing Metro Operations to Reduce Overcrowding**
- Proposed adjustments based on demand:
  - **Increase trips by 20%** during **Morning and Evening Peaks** to accommodate heavy commuter traffic.
  - **Reduce trips by 10%** during **Midday and Late Evening** to optimize resources.
- Compared **original vs. adjusted trip frequencies** using visualizations.

## Conclusion 
- The analysis provides **data-driven insights** to improve Delhi Metro operations.
- Adjusting service frequency during peak hours can **reduce congestion and enhance commuter experience**.
- Further improvements can be made by incorporating **real-time passenger flow data**.

## Technologies Used 
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Visualization** (Scatter Plots, Bar Charts, Geographical Mapping)
- **Data Merging & Preprocessing** (Merging multiple datasets, time-based analysis)

## Future Enhancements 
- Integrating **real-time passenger footfall data** for more precise scheduling.
- Implementing **machine learning models** for predictive analysis of peak demand periods.
- Developing an **interactive dashboard** for metro planners to monitor and adjust scheduling dynamically.



