# Executive E-Commerce Sales & Revenue Optimization Dashboard

## Project Preview
Below is a snapshot of the final interactive dashboard canvas. Technical hiring managers can download the raw `ecommerce-sales-analytics.pbix` file from this repository to review the full relational data model, internal documentation logs, and active DAX formulas from their own computers.

![Dashboard Preview](dashboard_screenshot.png)

## Project Overview
This BI project delivers an interactive dashboard tracking $10.64M in transactions for a global e-commerce retailer. It connects digital web activity with financial statistics to show high-grossing products, seasonal revenue trends, and international performance sales funnels.

## Data Engineering & Cleaning Steps (Power Query)
* **Transaction Filtering**: Structured data filters to isolate active sales cycles by removing transactional returns and order cancellations where Quantity ≤ 0.
* **Global Schema Alignment**: Used a Locale Transformation (English-US format conversion) to fix cross-regional text mismatches across 300,000+ localised date rows.
* **Calculated Business Logic (DAX)**: Programmed a granular calculated column layer multiplying unit cost by quantity to find the exact row-level Gross Revenue.

## Executive Insights & Business Value
* **International Market Concentration**: The United Kingdom stands as the primary financial driver, generating the overwhelming majority of global net sales revenue. 
* **Seasonal Sales**: Timeline trends indicate a significant spike in transaction volume during late Q4 (November and December), which matches with holiday shopping data.
* **Product Efficiency**: Isolated the top 5 highest-grossing product SKUs using Top-N visual filters, allowing supply chain managers to better manage inventory.

## Technical Features Included
* **Interactive Slicers**: Dynamic cross-filtering by country across all visuals.
* **State Bookmarks**: Applied 'Reset Filters' buttons to enhance user experience allowing them to easily clear their selections.
* **Granular Matrix Ledgers**: Drill-down choices from individual invoice sheets down to exact product line-items.
# ecommerce-revenue-optimisation-bi
