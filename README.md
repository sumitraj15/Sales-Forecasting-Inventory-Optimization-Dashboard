# Sales Forecasting & Inventory Optimization Dashboard

## Project Overview
An interactive Power BI dashboard designed to forecast product demand, monitor inventory availability, and support stock replenishment and purchase planning across three retail store locations: Gaur City, Sector 78 Noida, and Indirapuram.

The dashboard covers **120 SKUs** and uses moving-average forecasting to help identify potential stock shortages and make data-driven inventory decisions.

## Objectives
- Forecast next-day demand using historical sales trends.
- Compare forecasted demand against available warehouse stock.
- Identify SKUs requiring replenishment to reduce potential stockouts.
- Support store-level inventory planning and purchasing decisions.

## Tools & Technologies
- **Power BI** – Dashboard development and visualization
- **DAX** – Forecasting measures, inventory KPIs, and replenishment calculations
- **Excel** – Data preparation and analysis

## Forecasting Methodology
Two moving-average measures were implemented to estimate tomorrow's demand:

- **7-Day Moving Average:** Captures recent sales trends and short-term demand fluctuations.
- **30-Day Moving Average:** Provides a more stable estimate by smoothing daily variations.

The final forecast combines both measures to balance recent demand patterns with longer-term trends.

## Key Dashboard Features

### 1. KPI Overview
- Tomorrow Forecast
- Warehouse Stock
- SKU Below Demand
- Total Units to Order

### 2. Demand vs. Inventory Analysis
Compares forecasted demand with available stock for individual products to highlight potential inventory shortages.

### 3. Automated Replenishment Planning
Identifies products requiring refill and displays SKU-level and store-level stock information, forecasted demand, and recommended order quantities.

### 4. Store-Level Forecasting
Tracks forecasted demand across:
- Gaur City (ST01)
- Sector 78 Noida (ST02)
- Indirapuram (ST03)

### 5. Interactive Filtering
Enables users to filter dashboard insights by store and SKU to investigate inventory requirements at a granular level.

## Key Insights Displayed
The dashboard screenshot illustrates the following results for the selected filters:

| Metric | Value |
|---|---:|
| Tomorrow's Forecast | 445 units |
| Warehouse Stock | 6K units |
| SKUs Below Demand | 15 |
| Total Units to Order | 178 units |
| Gaur City Forecast | 150 units |
| Sector 78 Noida Forecast | 133 units |
| Indirapuram Forecast | 163 units |

*These values represent the dashboard snapshot and may change with the selected filters and underlying data.*

## Business Impact
- Improves visibility into future inventory requirements.
- Helps identify products at risk of stockouts.
- Supports systematic replenishment and purchasing decisions.
- Enables store-level demand planning through interactive reporting.

## Project Outcome
Developed an interactive inventory planning solution that combines moving-average forecasting, DAX-based KPIs, and replenishment analysis into a single dashboard for retail decision-making.

## Future Enhancements
- Integrate machine learning models for demand forecasting.
- Incorporate promotional events, pricing, and seasonality.
- Add supplier lead times and safety-stock calculations.
- Evaluate forecast accuracy using MAE, RMSE, and other relevant metrics.
