# Construction Labor & Margin Tracker | Power BI

A Power BI dashboard built to help construction teams spot labor overruns, overtime pressure, and margin issues earlier.

This report gives a quick executive view of:
- total overtime hours
- total actual labor cost
- total project budget
- labor variance by project
- overtime drivers by trade

## Why I built this

On most projects, problems do not show up all at once.

They usually start small:
- a bit too much overtime
- a few jobs running hot
- margin getting thinner before anyone clearly flags it

This dashboard is designed to make that visible faster.

## Dashboard preview

<img width="2075" height="1200" alt="Generated_chart__construction-labor-margin-tracker-preview png" src="https://github.com/user-attachments/assets/03749d96-8827-4bc8-8346-a6201de9c7cb" />


## What’s inside

- KPI cards for overtime hours, actual labor cost, and total project budget
- Project margin health view using labor variance
- Overtime breakdown by trade
- Project-level filtering for easier review

## Tools used

- Power BI
- DAX
- Power Query
- Excel / CSV data

## Data model

This project uses two connected tables:

- `construction_labor_logs`
- `construction_projects_summary`

They are linked through `Project_ID`.

## Notes

- Actual labor can be calculated from labor log activity
- Budget values are stored at project level
- Because budget is project-level, it stays fixed while labor activity can change based on filters

## How to use

1. Download the `.pbix` file from this repository
2. Open it in Power BI Desktop
3. Review the executive summary page
4. Use the project slicer to filter the dashboard
