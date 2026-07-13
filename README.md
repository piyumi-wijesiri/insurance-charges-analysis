# Health Insurance Charges Analysis

## Question
What actually drives health insurance charges — and how do these factors interact?

## Data
1,338 insurance records including age, sex, BMI, number of children, smoker status,
region, and the actual insurance charges billed.

## Tools
Python, pandas, matplotlib, numpy

## Key Findings
- Smokers are charged roughly 4x more than non-smokers on average 
  ($32,050 vs $8,434).
- BMI's effect on charges is almost entirely concentrated in smokers: among 
  smokers, high BMI (30+) roughly doubles charges compared to low-BMI smokers 
  ($41,808 vs $22,573) — but for non-smokers, BMI barely moves charges at all 
  ($8,893 vs $7,976).
- This suggests BMI isn't a strong cost driver on its own — it's smoking that 
  turns BMI into a major risk factor.
- Age, sex, region, and number of children all showed weaker relationships 
  with charges by comparison, with children showing almost no relationship 
  at all.

## Visualizations
- Insurance charges vs BMI, smokers vs non-smokers (scatter plot)
- Distribution of charges: smokers vs non-smokers (histogram with average lines)

## How to view
Open `insurance_charges_analysis.ipynb` to see the full analysis, code, and charts.