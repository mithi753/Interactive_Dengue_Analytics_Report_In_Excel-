# 🦠 Dengue Patient Analysis & Dashboard.
##  Project Overview
This project analyzes [dengue patient data](https://drive.google.com/file/d/1SIIQPJ-18PdhUO_4MC2OeR0pJYklcj68/view?usp=sharing) based on demographics, housing, and geographic locations in Dhaka. The dataset was explored using Excel (pivot tables, summaries) and [dashboards](https://drive.google.com/file/d/1FuUDC26Da8Vyw3_AvHxkn2XBn9vgFg7X/view?usp=sharing) , leading to important public health insights about dengue prevalence across different groups.
The findings highlight risk factors such as gender, living area type, and age distribution.
## Repository Structure

 * Dataset/→ Contains raw dengue dataset.

 * Pivot Tables/ → Summary analysis (age, gender, area type, house type).

 * Dashboard/ → Excel/Power BI dashboard for visualization.

 * Insights/ → Key findings from the dataset .
## Dataset Description
| Column        | Description                                                 |
| ------------- | ----------------------------------------------------------- |
| Gender        | Patient gender (Male/Female)                                |
| Age           | Age of patient                                              |
| NS1, IgG, IgM | Dengue diagnostic test results (0 = Negative, 1 = Positive) |
| Area          | Patient’s locality                                          |
| AreaType      | Developed / Undeveloped classification                      |
| HouseType     | Type of housing (Building, Tin-shed, Other)                 |
| District      | District (Dhaka sub-areas)                                  |
| Outcome       | Dengue outcome (0 = Negative, 1 = Positive)                 |
## Key Insights
 ### 1. Total Patients → 533 dengue patients identified.
      * Female: 281
      * Male: 252
### ✅ Females are at slightly higher risk than males.
### 2. By Area Type
      * Undeveloped areas: 276 cases
      * Developed areas: 257 cases
### ✅ Residents in undeveloped areas face a higher risk.

### 3. By Housing Type
      * Building: 191 cases
      * Tin-shed: 173 cases
### ✅ Surprisingly, building residents are at higher risk than tin-shed residents.

### 4. By Female Age Groups & Area

       * 15–24 yrs females in Rampura are most affected compared to Gulshan, Mirpur, Demra, New Market.

       * 25–34 yrs females in Gulshan are most affected compared to other Dhaka areas.

### 5. By Male Age Groups & Area

       * 25–34 yrs males in Tejgaon are most affected compared to other Dhaka regions.
     
### Dashboard Features
The dashboard visualizes:

* Gender distribution of dengue patients.
* Area-wise and housing-type risk analysis.
* Age-group and location breakdown.
* Comparison between developed vs undeveloped areas.
### Tools & Technologies
Excel (Pivot Tables, Charts, Dashboard)

### Future Work
* Apply machine learning for predictive modeling of dengue risk.
* Automate updates with Python + Power BI integration.
* Add time-series analysis if temporal data is available.
