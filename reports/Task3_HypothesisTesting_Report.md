# Task 3 - Hypothesis Testing Results

**Dataset:** data/MachineLearningRating_v3.txt

**Alpha:** 0.05


## Tests performed

- Claim Frequency by Province (Chi-squared)

- Claim Severity by Province (ANOVA / Kruskal-Wallis)

- Margin by Province (ANOVA / Kruskal-Wallis)

- Postal code pairwise comparisons (top 2 by count) — proportions z-test, severity & margin tests

- Margin across postal codes (ANOVA / Kruskal-Wallis)

- Gender comparisons: frequency (z-test), severity (t/Mann-Whitney), margin (t/Mann-Whitney)


## Summary - Fill with decisions from notebook outputs

- Provinces (frequency): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Provinces (severity): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Provinces (margin): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Postal codes (frequency top2): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Postal codes (margin top2): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Postal codes (margin multi-group): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Gender (frequency): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Gender (severity): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)

- Gender (margin): REPLACE_WITH_DECISION (p = REPLACE_WITH_P)


## Business Recommendations (example templates)

- If you reject H0 for Province frequency/severity: "We REJECT H0 (p < 0.05). Province X shows higher claim frequency/severity — recommend revising premiums or underwriting criteria in Province X."

- If you reject H0 for PostalCode margin: "We REJECT H0 (p < 0.05). Postal code Y shows lower margins — consider investigating local risk factors and adjusting pricing or marketing strategy."

- If you find gender differences: "We REJECT H0 (p < 0.05). Differences between genders exist for KPI Z — evaluate potential causes and ensure non-discriminatory underwriting."

