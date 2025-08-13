# Major Adverse Cardiovascular Outcomes for Semaglutide and Tirzepatide in Clinical Practice


# Supplementary Analysis Code

This repository contains illustrative code related to the study of **major adverse cardiovascular outcomes (MACE)** among patients treated with **semaglutide** or **tirzepatide** in clinical practice.

**ClinicalTrials.gov IDs**: [NCT06659744](https://clinicaltrials.gov/study/NCT06659744), [NCT07088718](https://clinicaltrials.gov/study/NCT07088718), [NCT07096063](https://clinicaltrials.gov/study/NCT07096063)

---

## 🧪 About the Analysis

Primary analyses were conducted on the **Aetion Evidence Platform**, a validated system for generating regulatory-grade real-world evidence and trial emulations. The platform has been benchmarked against FDA Sentinel workflows and evaluated in the RCT-DUPLICATE initiative.

The code provided here is **not sufficient to replicate study results**, as it:
- Does **not include source data** (privacy and data-use restrictions)
- Supplements the Aetion-based analysis by illustrating downstream steps:
  - Post-processing of exported results
  - Plotting and figure generation
  - Follow-up time summaries

> **Outcome focus:** Unless otherwise specified in a given script, MACE refers to **all-cause mortality, myocardial infarction, or stroke** (composite), with components analyzed separately in secondary analyses and compeleted with other outcome analyses.

---

## 📁 Contents

| Script | Purpose |
|--------|---------|
| `Cumulative_Incidence_Curve.ipynb` | Plots cumulative incidence curves for **MACE** from matched cohorts. |
| `Forest_plots.ipynb` | Generates forest plots from summary tables of **treatment effects** across databases. |
| `Mean_FUP.ipynb` | Summarizes **mean/median follow-up**. |

---

## 📦 Dependencies

These scripts require:

- `pandas`
- `numpy`
- `matplotlib`
- `lifelines`
- `seaborn` *(optional; used in some visualizations)*

Install via:

```bash
pip install -r requirements.txt
