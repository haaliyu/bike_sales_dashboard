# Case Study: Bike Sales Performance & Demographics Dashboard

## 1. Project Overview
* **Objective:** Clean, transform, and model raw customer data to build an interactive business intelligence tool evaluating retail bike purchasing drivers.
* **Tool Stack:** Microsoft Excel (Advanced Data Cleaning, Nested Formulas, Pivot Tables, Interactive Slicers, Dynamic Charting).
* **Target Audience:** Retail Sales Operations Leaders, Regional Directors, and Demographic Marketing Strategy Teams.

## 2. Business Challenge & Core Questions
The retail team lacked visibility into why specific demographic subsets converted at different rates, resulting in broad marketing spending instead of targeted regional campaigns. This dashboard addresses:
* **Income Elasticity:** Does personal income accurately predict conversion rates across genders?
* **Age Bracket Optimization:** Which customer lifecycle stage represents the largest volume opportunities?
* **Commute Constraints:** At what distance thresholds do customers transition away from functional cycling?

## 3. Data Architecture & Pipeline Steps
1. **Data Cleaning:** Extracted raw tables, removed duplicate rows, resolved blank text entries, and unified syntax structure.
2. **Feature Engineering:** Created an `Age Brackets` column using nested `IF` statements to group raw customer ages into three definitive segments: `Adolescent`, `Middle Age`, and `Senior`.
3. **Data Modeling:** Developed independent dynamic Pivot Tables isolating targeted metrics while keeping unified data relationships.
4. **UI Design:** Implemented standardized metric tiles, consistent brand-aligned color coding, and connected slicers across charts for localized slicing.

## 4. Key Performance Insights
* **The Income Threshold:** Higher average household earnings directly correlate with a higher probability of purchasing a bike across both genders.
* **The Middle-Age Peak:** Customers within the Middle Age cluster show the highest total acquisition volumes compared to other life phases.
* **The Distance Drop-off:** Short-distance commuters (0–1 miles) demonstrate the highest conversion, which dramatically tapers as commute lengths exceed 2–5 miles.
* **The Household Size Impact:** Bike purchases are highest among households with zero children, showing a significant downward trend in purchase counts as the number of children increases.

## 5. Strategic Business Recommendations
* **Micro-Targeted Campaigns:** Direct localized digital ad spending exclusively toward high-income middle-aged cohorts in urban centers.
* **Product Line Diversification:** Shift inventory allocations toward functional commuter lines in short-range areas while prioritizing high-end hobby gear in affluent regions.
