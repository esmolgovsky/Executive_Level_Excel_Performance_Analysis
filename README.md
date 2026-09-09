# Executive Level Excel Sales Rep Performance Analysis
An Excel workbook analyzing sales rep performance, quota attainment, pipeline health, commission payouts, and pipeline coverage against quota. All three dashboard tabs are formula-driven (no hardcoded values) and update automatically when you change a control cell or the underlying data.

## Download the dile or watch the recording to see how it works!

## Tabs
- **Executive Summary** shows company-wide KPIs and 24-month trend, team/region rollups, rep leaderboard, pipeline/funnel health, and risk flags.
- **Commission Calculator** shows an illustrative tiered commission model (base rate up to 100% of quota, accelerator from 100–150%, super-accelerator beyond 150%), with editable rates by role and an eligibility threshold. **Rates shown are illustrative assumptions for analysis, not an actual comp plan.**
- **Pipeline Coverage** shows a gap-to-goal and pipeline coverage ratio by rep/team/region, flagging reps whose open pipeline (and their own historical win rate) can't mathematically get them to goal.
- **Monthly_Summary, Dim_Reps, Fact_Quota, Fact_Pipeline, Dim_Date, Lookups** is the underlying data model the three dashboards are built on.

## How to use it
Each dashboard tab has a controls bar near the top (reporting month, performance window, and tab-specific assumptions like target coverage ratio or commission rates). Changing any of these recalculates the whole tab (KPI tiles, tables, and charts) automatically.
