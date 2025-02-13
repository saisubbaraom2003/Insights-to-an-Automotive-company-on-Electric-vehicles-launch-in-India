# Electric Vehicle (EV) Sales Analysis in India

## Project Overview
This project aims to analyze electric vehicle (EV) sales data in India, providing insights for companies looking to launch EVs in the Indian market. The analysis covers sales trends by state, manufacturer, and overall market penetration, helping stakeholders make data-driven decisions.

## Datasets
The project utilizes three key datasets:

### 1. `electric_vehicle_sales_by_state.csv`
Contains sales data of EVs across different Indian states.
- **date**: The recorded date in the format `DD-MMM-YY` (monthly data).
- **state**: Name of the state where sales occurred.
- **vehicle_category**: Either `2-Wheeler` or `4-Wheeler`.
- **electric_vehicles_sold**: Number of EVs sold in that state and category.
- **total_vehicles_sold**: Total number of vehicles (electric + non-electric) sold in that state and category.

### 2. `electric_vehicle_sales_by_makers.csv`
Tracks EV sales by manufacturers.
- **date**: Sales recording date in `DD-MMM-YY` format.
- **vehicle_category**: Either `2-Wheeler` or `4-Wheeler`.
- **maker**: Manufacturer or brand name.
- **electric_vehicles_sold**: Number of EVs sold by the maker in the given category.

### 3. `dim_date.csv`
A date dimension table useful for time-series analysis.
- **date**: Specific date in `DD-MMM-YY` format.
- **fiscal_year**: The fiscal year (`April 1st - March 31st` in India).
- **quarter**: Fiscal quarter (`Q1`, `Q2`, `Q3`, or `Q4`).

## Key Metrics & Insights

### 1. Penetration Rate
Indicates EV adoption levels in different regions and categories.
**Formula:**
```
Penetration Rate = (Electric Vehicles Sold / Total Vehicles Sold) * 100
```

### 2. Compound Annual Growth Rate (CAGR)
Measures long-term EV sales growth.
**Formula:**
```
CAGR = ((Ending Value / Beginning Value) ^ (1/n)) -1
```

## Goals of the Analysis
- Identify the best-performing states for EV sales.
- Analyze market trends and penetration rates.
- Determine leading EV manufacturers in India.
- Provide recommendations for launching EVs in India based on sales patterns and growth trends.

## Next Steps
- Perform exploratory data analysis (EDA) on the datasets.
- Visualize sales trends across states and manufacturers.
- Compute penetration rates and CAGR.
- Provide strategic recommendations for EV market entry in India.

## Tools Used
- **Python** (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)


---
This project aims to offer data-driven insights for companies planning to enter the Indian EV market, ensuring informed business decisions based on real-world data.

