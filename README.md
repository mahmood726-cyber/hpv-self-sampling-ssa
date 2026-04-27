# HPV Self-Sampling for Cervical Cancer Screening in Sub-Saharan Africa

## Overview
A world-class, multi-persona reviewed meta-analysis estimating the pooled proportion of HPV self-sampling uptake among women in Sub-Saharan Africa.

## Methodological Upgrades
Following a Multi-Persona Review (Statistical Methodologist, Clinical Domain Expert, Editorial Reviewer), this repository was upgraded to "world class" standards:
- **Statistical rigor**: Shifted to **Logit Transformed Proportions (PLO)** using `metafor::escalc`.
- **Small-k corrections**: Implemented the **Knapp-Hartung adjustment** (`test="knha"`).
- **Sensitivity analysis**: Included a leave-one-out sensitivity analysis.
- **Visualizations**: Added a funnel plot for publication bias and improved the forest plot layout.
- **Clinical terminology**: Updated E156 text to use non-stigmatizing language ("priority demographic").

## Quick Start
Run the analysis in R:
```bash
cd code
Rscript meta_analysis.R
```