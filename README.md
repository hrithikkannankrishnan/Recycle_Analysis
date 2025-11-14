## Analyzing Recycling Behavior at NUS

This repo contains code and materials for a field-data study of recycling interventions at NUS. We test whether shaped openings and informational banners reduce contamination in paper, plastic, and cans across ENGINE and UTOWN, using Difference-in-Differences (DiD), Interrupted Time Series (ITS), and bootstrap robustness. 

DBA5101 Recycle Analysis Final …

## Key Findings

Intervention efficacy: No reliable improvement overall (mixed / mostly null effects).

Priority contaminant: Plastic shows the highest contamination; target first.

Location signal: UTOWN exhibits higher baseline contamination than ENGINE.

Robustness: Results consistent under t-tests/ANOVA, median-DiD, and 10k bootstrap CIs. 

DBA5101 Recycle Analysis Final …

## Objectives

Quantify intervention effects on contamination rates.

Compare materials and sites; identify hotspots.

Provide actionable design/ops guidance for campus facilities. 

DBA5101 Recycle Analysis Final …

## Methods

DiD models (phase comparisons; phase-specific effects).

Median-based DiD for outlier robustness.

Bootstrap (10,000 iters) for empirical CIs.

ITS for level/slope changes across phases. 

DBA5101 Recycle Analysis Final …

## Data & Preparation

Contamination rates for paper/plastic/cans at ENGINE & UTOWN across three phases: Baseline → Shaped Openings → Banners.

Cleaning: drop rows with all-missing contaminants; treat isolated missing values; retain outliers (small-n). 

DBA5101 Recycle Analysis Final …

## Managerial Playbook

Design first: Prioritize shaped openings and bin ergonomics over banners.

Plastic-first: Dedicated receptacles, lid affordances, anti-overflow inserts.

Choice architecture: Co-locate trash + recycling; salient labels at eye level.

Feedback loops: Simple bin-side scorecards; targeted ops SOPs; site-specific emphasis (UTOWN focus). 

DBA5101 Recycle Analysis Final …

## Repository Structure

├─ data/                 # Input data (secured or dummy samples)
├─ notebooks/            # EDA, DiD, ITS, bootstrap analyses
├─ scripts/              # Reproducible pipelines (cleaning, modeling)
├─ results/              # Tables, figures, exported summaries
├─ README.md
└─ report/               # Final PDF/report
