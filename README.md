# Cyber Security Dashboard for Non-Technical Managers

**Author:** Md Shohrab Hossen Niaz  
**Focus:** governance  
**Visibility guidance:** public-ok

## Overview

Communication strength builder (supports your Feeling/Extroversion development goal).

## Research questions

1. What business problem does “Cyber Security Dashboard for Non-Technical Managers” solve for an SME or partner organisation?
2. Which artefacts demonstrate a credible, implementable solution?
3. How is success measured without overstating lab or synthetic evidence?

## Deliverables

- gap analysis
- roadmap
- reporting pack
- Report and presentation (`Final_Submission/`)
- Evaluation scorecard (`02_Evaluation/`)
- Design notes (`01_Design/`)
- Baseline evidence JSON (`evidence/`)

## Repository layout

```
01_Design/           Design and method notes
02_Evaluation/       Scorecard workbook
evidence/            Baseline evidence model
Final_Submission/    Report, slides, appendices
```

## Limits

Synthetic or laboratory baselines are labelled. No production tenant secrets. Where a topic could imply offensive techniques, this pack stays defensive and high-level.

**GitHub:** `sme-cyber-dashboard-managers`


## Run the automation

Working code is in `src/`. Sample inputs are in `data/`. Results write to `output/`.

```powershell
.\automation\run.ps1
```

Manual:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python -m src.cli run
python tests\test_smoke.py
```

Domain engine kind: `governance`.

**Author:** Md Shohrab Hossen Niaz  
**GitHub:** `sme-cyber-dashboard-managers`
