# Celebal Internship - Week 2 (SQL & Data Analysis)

This repository contains my submissions for the Week 2 tasks of the Celebal Technologies internship. The work is split into two distinct notebooks covering basic SQL data exploration, core query components, database design patterns, and transactional logic.

## Project Structure
* `Assignment2.ipynb` - Initial project task focusing on loading data, profiling schema structures, and basic GROUP BY aggregates using the superstore dataset.
* `SQL_Task2_Week2.ipynb` - Detailed task notebook addressing all 27 business queries, constraint logic test use cases, and advanced transaction workflows specified in the PDF assignment brief.
* `cleaned_superstore.csv` - The formatted, clean output dataset generated during execution.

## Core Tasks Handled
1. **Schema & Database Initialization:** Modeled and structured e-commerce relational sets including custom rules like constraints (Primary Keys, Foreign Keys, and CHECK rules).
2. **Data Filtering:** Applied WHERE parameters across regional and performance targets.
3. **Aggregations & Metrics:** Calculated descriptive groupings (SUM, COUNT, AVG, MIN, MAX) to view operational performance patterns across order statuses and store categories.
4. **Relational Table Joins:** Implemented multi-table INNER and LEFT JOIN logic to combine customer tracking attributes and calculate user lifetime margins.
5. **Conditional Logic & Integrity Blocks:** Structured price level sorting maps using CASE expressions and generated a full ACID-compliant rollback model (`BEGIN TRANSACTION ... COMMIT / ROLLBACK`) to handle error states.
