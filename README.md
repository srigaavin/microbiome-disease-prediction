# Microbiome-Based Disease Prediction: Analytics & Bioinformatics Hybrid Project

## 📋 Project Overview

A **dual-pathway data science project** combining computational biology and business analytics to predict Inflammatory Bowel Disease (IBD) from gut microbiome composition.

**Target Audience**: 
- Bioinformatics researchers (publishable findings)
- BI/Analytics professionals (data pipeline, ML, dashboards)
- Healthcare startups (clinical prediction model)

---

## 🎯 Objectives

1. **Scientific**: Identify bacterial taxa associated with IBD; validate against literature
2. **Analytics**: Build predictive model (85%+ accuracy); create interactive dashboard
3. **Portfolio**: Demonstrate Python, SQL, Power BI, statistical analysis skills

---

## 📊 Key Results (Target)

| Metric | Expected Value |
|--------|-----------------|
| Model Accuracy | 83–85% |
| AUC-ROC | 0.85–0.90 |
| Top Predictive Bacteria | 5–10 taxa |
| Samples Analyzed | 1,000+ |
| Visualizations | 15+ plots + Power BI dashboard |

---

## 🗂️ Project Structure
microbiome-disease-prediction/
├── data/                          # Raw & processed data
│   ├── metadata.csv              # Sample metadata
│   ├── abundance_table.csv       # Bacterial abundance (features)
│   └── processed_features.csv    # ML-ready features
│
├── code/                          # Python scripts & notebooks
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_diversity_analysis.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_ml_model.ipynb
│   ├── 05_database_setup.py
│   └── requirements.txt
│
├── results/                       # Plots, model outputs
│   ├── 01_diversity_distribution.png
│   ├── 02_top_bacteria.png
│   ├── 03_abundance_heatmap.png
│   ├── 04_roc_curve.png
│   ├── model_metrics.csv
│   └── feature_importance.csv
│
├── dashboard/                     # Power BI files
│   ├── microbiome_dashboard.pbix
│   └── dashboard_screenshots/
│
├── paper/                         # Written results
│   ├── METHODOLOGY.md
│   ├── RESULTS_SUMMARY.md
│   └── FIGURES.md
│
├── README.md                      # This file
└── .gitignore
---

## 🔬 Technical Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Data Processing** | Python (Pandas, NumPy) | Load, clean, transform data |
| **Bioinformatics** | SciPy, Scikit-bio | Diversity metrics, statistics |
| **Machine Learning** | Scikit-learn | Random Forest, model evaluation |
| **Database** | SQLite | Structured data storage |
| **Visualization** | Matplotlib, Seaborn, Power BI | Plots & dashboards |
| **Version Control** | Git/GitHub | Reproducible science |

---

## 📈 Week-by-Week Timeline

| Week | Phase | Deliverables |
|------|-------|--------------|
| **1** | EDA & Diversity | 3+ plots, diversity metrics |
| **2–3** | Feature Engineering | Processed dataset, statistical tests |
| **4–5** | ML Modeling | Trained model, ROC curve, feature importance |
| **6** | Database Design | SQLite schema, populated tables |
| **7** | Power BI Dashboard | Interactive 5-page dashboard |
| **8** | Documentation | GitHub repo, README, results summary |

---

## 🚀 Quick Start

### Prerequisites
```bash
# Python 3.9+
# Conda/Miniconda installed
# Git installed
```

### Setup
```bash
# Clone repository
git clone https://github.com/[YOUR-USERNAME]/microbiome-disease-prediction.git
cd microbiome-disease-prediction

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r code/requirements.txt

# Start Jupyter
jupyter lab
```

### Run Analysis
```bash
# Open notebooks in Jupyter Lab
# 01_exploratory_data_analysis.ipynb (start here)
# Follow execution order: 01 → 02 → 03 → 04 → 05
```

---

## 📝 Key Analyses Performed

### Phase 1: Exploratory Data Analysis
- **Alpha Diversity**: Shannon & Simpson indices
- **Beta Diversity**: Bray-Curtis distances (planned Week 2)
- **Taxonomic Profiling**: Top 10 taxa by abundance
- **Descriptive Statistics**: Sample counts, missing values, distributions

### Phases 2–3: Feature Engineering
- Relative abundance normalization
- Log transformation
- Feature selection (top 50 taxa)
- Disease group comparison (statistical tests)

### Phases 4–5: Predictive Modeling
- **Model**: Random Forest Classifier
- **Evaluation**: 5-fold cross-validation, AUC-ROC, confusion matrix
- **Interpretation**: Feature importance (which bacteria predict disease?)

### Phases 6–7: Dashboarding
- **KPI Cards**: Model accuracy, sample count, diversity metrics
- **Interactive Slicers**: Filter by disease, age group, diversity level
- **Drill-Through**: Click a sample → see detailed microbiome profile

---

## 📊 Data Dictionary

| Column | Type | Description |
|--------|------|-------------|
| `sample_id` | string | Unique sample identifier |
| `patient_id` | integer | Unique patient identifier |
| `disease_status` | string | healthy / IBD |
| `age` | integer | Patient age (years) |
| `bmi` | float | Body Mass Index |
| `shannon_diversity` | float | Alpha diversity metric |
| `num_taxa` | integer | Count of detected bacteria |
| `top_taxa_[1-10]` | float | Relative abundance of top 10 bacteria |

---

## 🔍 Research Questions

1. **Q1**: Which bacterial taxa are significantly different between healthy and IBD samples?
2. **Q2**: Can we predict IBD status from microbiome composition alone?
3. **Q3**: What is the model's sensitivity & specificity for clinical use?
4. **Q4**: Are diversity metrics correlated with disease severity?

---

## 📚 References

- QIIME2 Documentation: https://docs.qiime2.org/
- Scikit-learn ML Guide: https://scikit-learn.org/
- Microbiome Analysis Papers:
  - Locey & Lennon (2016): "Scaling laws predict global microbial diversity"
  - Human Microbiome Project: https://www.hmpdacc.org/

---

## 👨‍💻 Author & Contact

**Student**: Srigaavin R.K. B.Tech Biotechnology(Computational Biology), SRM University
**Project Date**: May-June 2026
**Repository**: https://github.com/srigaavin/microbiome-disease-prediction

---

## 📋 Checklist for Submission

- [ ] All code notebooks uploaded to GitHub
- [ ] All plots saved in `/results/` (300 DPI)
- [ ] Power BI dashboard exported as `.pbix` + PDF
- [ ] Database schema documented
- [ ] README complete with all sections
- [ ] At least 10 commits with clear messages
- [ ] LinkedIn post with project summary
- [ ] Ready for portfolio & university submission

---

**Last Updated**: May 30, 2026
**Status**: 🟡 Phase 3 in progress
