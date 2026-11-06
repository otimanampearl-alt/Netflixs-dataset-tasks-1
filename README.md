# Netflix Data Cleaning & Chart Preparation

## Project Overview

This project uses Microsoft Excel to prepare and analyse a Netflix Movies and TV Shows dataset. The work focuses on checking and organising the data, summarising it with PivotTables, creating charts, and communicating findings in a clear way.

The main question for the content-distribution analysis is:

**How is the Netflix catalogue in this dataset distributed between Movies and TV Shows?**

The workbook also contains additional exploratory summaries covering countries, years, ratings, directors, TV Show seasons, and movie durations.

## Project Instructions

**Task 1 (Easy) – Data Cleaning & Chart Preparation**

**Description:** Prepare the Netflix dataset and create basic visualisations to understand content distribution.

### Workflow

1. Import the dataset into Microsoft Excel.
2. Check for missing and duplicate records and prepare the data for analysis.
3. Create PivotTables to summarise the dataset.
4. Generate charts to communicate the results.
5. Summarise key findings and observations.

### Key Features

- Data cleaning and preparation
- PivotTable analysis
- Basic charts and visualisation
- Summary of findings

### Skills Applied

- Microsoft Excel
- Data organisation
- Data quality checks
- PivotTables
- Chart creation
- Data storytelling

## Dataset

The workbook contains a cleaned-data worksheet with **8,790 records** and 10 columns:

`Show_ID`, `Type`, `Title`, `Director`, `Country`, `Date_Added`, `Release_Year`, `Rating`, `Duration`, and `Listed_In`.

The `Show_ID` field has no duplicate values in the supplied cleaned dataset. The worksheet also contains placeholder text such as `Not Given` for some unavailable information; these values should be treated as unavailable data rather than actual names or locations.

## Workbook Contents

| Worksheet | Description |
|---|---|
| `Cleaned Data` | Prepared Netflix dataset used for analysis |
| `Pivot Tables` | Summary tables for content type, country, year, rating, and other attributes |
| `charts` | Eight visualisations presenting patterns in the dataset |
| `Key Findings` | Written observations and overall findings |

## Key Findings

### Content type

| Content Type | Titles | Share |
|---|---:|---:|
| Movies | 6,126 | 69.7% |
| TV Shows | 2,664 | 30.3% |
| **Total** | **8,790** | **100%** |

Movies make up the larger share of the catalogue represented in this dataset, with more than twice as many Movies as TV Shows.

### Other observations in the workbook

- **Country:** The United States has the highest country-associated title count in the workbook's country summary (3,240), followed by India (1,057) and the United Kingdom (638).
- **Year added:** 2019 has the highest count in the workbook's year-added summary (2,016).
- **Content rating:** TV-MA is the most common rating (3,205), followed by TV-14 (2,157).
- **TV Show seasons:** Most TV Shows in the dataset have one season (1,791).
- **Movie duration:** The workbook's duration summary identifies 90 minutes as the most frequent movie duration (152).

**Data interpretation note:** Country values can represent more than one country for a title, and unavailable values are represented in places by `Not Given`. Counts should therefore be interpreted as dataset records or country associations, not as exclusive market shares. Catalogue counts alone do not measure audience popularity, viewing time, or revenue.

## The Three Data Analyst Questions

### 1. What did I analyse, and what question was I trying to answer?

I analysed the Netflix Movies and TV Shows dataset, beginning with its content-type distribution. The main question was how many Movies and TV Shows were represented in the catalogue and what proportion each category contributed. The workbook also explores country, year, rating, director, season, and movie-duration patterns.

### 2. What specific findings did the analysis reveal?

Out of 8,790 titles, 6,126 (69.7%) are Movies and 2,664 (30.3%) are TV Shows. The United States has the highest country-associated count in the country summary, while TV-MA is the most common content rating. The workbook includes further findings in the `Key Findings` worksheet.

### 3. What actions could these findings support?

The content-type distribution could support a review of the balance between Movies and TV Shows in the catalogue. The country and rating summaries could also inform further questions about content sourcing and catalogue mix. These findings are starting points for business discussion; decisions should also consider audience engagement, viewing performance, costs, and strategic objectives.

## How to Use the Workbook

1. Download `Netflix_Data_Cleaning_and_Analysis.xlsx` from this repository.
2. Open it in Microsoft Excel.
3. Select `Cleaned Data` to view the prepared dataset.
4. Select `Pivot Tables` to review the summaries.
5. Select `charts` to explore the visualisations.
6. Select `Key Findings` to read the written observations.

## Project File

- `Netflix_Data_Cleaning_and_Analysis.xlsx` — Excel workbook containing the dataset, PivotTables, charts, and findings.

## Conclusion

This project demonstrates how Microsoft Excel can be used to prepare data, summarise records with PivotTables, create visualisations, and communicate findings. It also highlights the importance of interpreting results carefully and connecting data findings to practical business questions.
