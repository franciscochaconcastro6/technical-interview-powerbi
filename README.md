# Technical Interview – Power BI Report

**Author:** Francisco Chacón

## Objective
One-page report for leadership on 2025 performance across four automotive service brands.

## Files
| File | Description |
|---|---|
| `report.pbix` | Power BI file with the data model, DAX measures and visuals |
| `report.pdf` | Exported report, viewable directly on GitHub |

## Data cleaning
- Removed 15 duplicated rows in `tickets` (4,797 → 4,782).
- Only `COMPLETED` tickets count as sales; cancellation and refund rates use all tickets.
- <!-- other issues found -->

## Data model
Star schema: `tickets` as the fact table, with `stores`, `customers` and a `Date` table as dimensions.

## Key findings
1. <!-- finding with its number -->
2. <!-- finding -->
3. <!-- finding -->

## Next steps
- <!-- what you would validate with the business -->
