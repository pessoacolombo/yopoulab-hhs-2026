# Yopougon Urban Lab (YopouLab) — 2026 Household Survey Report

Interactive report of the **YopouLab exploratory household survey** conducted in
April–May 2026 in the Millionnaire-Extension area of Yopougon, Abidjan
(Côte d'Ivoire). Published with GitHub Pages.

**Live site:** `https://pessoacolombo.github.io/yopoulab-hhs-2026/report/index.html`

## Pages

| Page | File | Content |
|---|---|---|
| Descriptive Report | `index.html` | Full descriptive results: overview map, built environment & urban morphology, household characteristics, housing conditions, mobility, healthcare access, demographics, mental health & wellbeing, age-friendly environments, urban health priorities, and heat stress |
| Bivariate Explorer | `bivariate.html` | Interactive cross-tabulations between survey variables |
| Stratum Profiles | `profiles_summary.html` | Summary cards and radar charts comparing the three habitat strata |

## The survey

- **1,495 households** interviewed, with a sub-sample of **1,981 adults** and a
  household roster covering **7,286 members**.
- **32 clusters** drawn quasi-randomly across three habitat strata —
  **Informal / Hybrid / Formal** — defined from Earth-observation-based
  morphometric analysis of the built environment.
- Conducted by the **YopouLab consortium**, coordinated by the
  [Swiss Tropical and Public Health Institute (Swiss TPH)](https://www.swisstph.ch/) and the
  [Centre Suisse de Recherches Scientifiques en Côte d'Ivoire (CSRS)](https://www.csrs.ch/)

## Data & privacy

This repository contains **only the rendered static site**. All figures and
tables are built from **aggregated data** (stratum- or cluster-level); no
individual- or household-level records are published here. Cluster locations
shown on maps are generalised survey areas, not respondent addresses.

## How the site is built

The report is authored in Quarto (Python / Plotly) and
rendered locally from an aggregation pipeline that is not part of this
repository for data privacy reasons. The files here (`index.html`, `bivariate.html`,
`profiles_summary.html`, `site_libs/`, `custom.css`, `search.json`) are the
rendered output.

## License & citation

Results are preliminary and descriptive; please contact the YopouLab
[consortium coordinator](https://www.swisstph.ch/en/staff/profile/people/vitor-pessoa-colombo) 
before citing or reusing any figures.

© YopouLab consortium / Swiss TPH & CSRS
