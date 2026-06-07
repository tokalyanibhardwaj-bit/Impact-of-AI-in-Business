# Impact of AI in Business — Power BI

A three-page Power BI report examining how AI adoption translates into measurable financial and operational outcomes across industries, countries, and technology types — spanning 2020 to 2026.

The question driving this project: is AI investment actually paying off, and for whom?

---

## What's inside

**Page 1 — Executive Overview**

The summary layer. Built for anyone who needs the full picture before drilling down.

Top-line numbers across the full dataset:

| Metric | Value |
|--------|-------|
| Total Investment | $556K |
| Total Revenue | $1.559M |
| ROI % | 180.60% |
| Avg AI Adoption Rate | 42.22% |
| Avg Automation Rate | 24.22% |
| Avg Productivity Gain | 18.01% |

The page has four slicers — Year, Country, Industry, and AI Technology — so the numbers above shift depending on what you're filtering for. The defaults show the full 2020–2026 range.

Visuals here: an AI adoption growth line (fairly flat across the period, which is itself interesting), a donut showing investment share by industry, a grouped bar comparing investment against revenue impact across sectors, and an Industry KPI Comparison table that lets you scan automation rate, AI adoption rate, and productivity gain side by side.

---

**Page 2 — Industry Performance Analysis**

Where the segmentation gets sharper. This page asks which industries are actually leading.

Headline figures: 78% highest AI adoption, 319.90% highest ROI, 44.79% highest productivity gain.

- **AI Adoption by Industry** (horizontal bar) — Information Technology leads, with Banking & Finance and Marketing & Advertising close behind; Customer Service sits at the bottom
- **ROI % by Industry** (bubble chart) — the bubble size and position both carry information; it's not always the highest-adoption industries generating the best ROI
- **Productivity Gain by Industry** (treemap) — gives a proportional sense of which sectors are getting the most operational lift
- **Revenue Impact Breakdown** (matrix) — sliceable by industry, country, and AI technology; useful for spotting geographic variation within a sector

---

**Page 3 — Financial Impact & Business Value**

The money page. Moves from adoption rates to hard financial outcomes.

$1.003M profit generated on $556K invested. The ROI holds at 180.60% across the dataset, but the breakdown by industry tells a more varied story.

- **Investment vs Revenue Impact** (bubble chart) — each bubble is an industry; the spread is wider than I expected; some industries are generating significantly more revenue per dollar invested than others
- **Revenue Contribution by Industry** (waterfall chart) — shows incremental and total contribution cleanly; Education lands at the far right as the cumulative total bar
- **Revenue Impact Trend** (line chart, 2020–2026) — rises steadily through 2024 then drops noticeably in 2025–2026; the drop is worth interrogating — could reflect dataset coverage tapering off toward the forecast years, or an actual modelled decline
- **Factor Driving Revenue Impact** (Key Influencers visual) — Power BI's built-in ML visual; surfaces what variables statistically correlate with increases in revenue impact

---

## Tools used

Power BI Desktop — data modelling, DAX, layout. Power Query for transformation. Custom DAX measures for the KPI cards, ROI calculation, and profit generated. The Key Influencers visual on Page 3 uses Power BI's native AI visual, which felt appropriate given the subject matter.

---

## A few things I noticed

The flat AI adoption growth line on Page 1 surprised me. Across 2020–2026 the average barely moves — which suggests that within this dataset, the variation is more cross-sectional (between industries) than longitudinal (over time).

The ROI bubble chart on Page 2 is the visual I'd linger on longest. IT has the highest adoption but doesn't always win on ROI — some mid-adoption sectors punch above their weight financially.

The revenue trend drop after 2024 on Page 3 is the one thing I'd want to interrogate further with more data. It could be a real finding or a dataset artefact. I've left it as-is rather than smoothing it out — the honest view of the data matters more than a cleaner chart.

---

## Why I built this

This is my second Power BI portfolio project. My background is in languages and humanities (B.A. German, University of Delhi), and I'm building toward a career in BI and data analytics. I picked an AI-focused dataset deliberately — it's a domain that's increasingly relevant to every industry conversation I want to be part of.

PL-300 certified. Open to feedback.
