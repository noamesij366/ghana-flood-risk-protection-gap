# Flood Disaster Risk Assessment and the Insurance Protection Gap in Ghana
Actuarial frequency-severity analysis of flood events in Ghana (2001–2023), 
using data from the EM-DAT International Disaster Database.

## Paper
The full paper is available in [`paper/Ghana_Flood_Risk_Protection_Gap.pdf`](paper/Ghana_Flood_Risk_Protection_Gap.pdf)

## Summary
- 25 flood events recorded between 2001 and 2023
- Poisson model estimates a 66.3% annual probability of at least one flood
- Lognormal severity model projects over 2 million persons affected in a 1-in-50-year event
- Insured losses across all events: **$0**, representing a 100% insurance protection gap

## Methodology
- **Frequency modelling:** Poisson distribution (MLE), Chi-square goodness-of-fit
- **Severity modelling:** Lognormal and Pareto distributions compared via AIC
- **Return period estimation:** Inverse CDF of fitted Lognormal distribution

## Repository Structure
ghana-flood-risk-actuarial-analysis/
│
├── README.md
├── LICENSE
├── paper/
│   └── Ghana_Flood_Risk_Protection_Gap.pdf
├── notebooks/
│   └── flood_risk_analysis.ipynb
├── data/
│   └── emdat_ghana_floods_2001_2023.xlsx
├── figures/
│   └── severity_distribution.png
└── requirements.txt
