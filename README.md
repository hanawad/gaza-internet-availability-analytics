# 🌐 Internet Availability & Connectivity Pattern Discovery

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
![Focus](https://img.shields.io/badge/Focus-Data%20Mining-6f42c1)
![Stack](https://img.shields.io/badge/Stack-Pandas%20%7C%20Scikit--learn-orange)

Discovering **when and where connectivity fails** across 15,000 synthetic records. Combines descriptive statistics, `K-Means`/`PCA` pattern discovery, and classification.

## 📊 Statistical Snapshot

| Metric | Result |
|---|---:|
| Internet availability | 43.2% |
| Mean disconnects (95% CI) | 3.70 (3.666–3.731) |
| Disconnects: SD · Skewness · Kurtosis | 2.04 · 0.00 · −0.96 |

`K-Means` segments records into four connectivity patterns; `PCA` projects clusters for inspection. `Gradient Boosting` led the recorded classifier comparison (F1 **0.9545**).

> **Caveat:** Data is synthetic, and classification features include variables tied to the target-generation logic. Treat model scores as exploratory, not real-world predictive performance.

## 📈 Visualizations

**1. Connectivity overview** — availability by hour, area comparison, quality, and overall summary.

![Connectivity summary dashboard](assets/connectivity_summary_dashboard.png)

**2. Availability patterns by day and hour**

![Availability heatmap](assets/availability_heatmap.png)

**3. Disconnect intensity by hour and area type**

![Disconnects heatmap](assets/disconnects_by_hour_area_type_heatmap.png)

**4. K-Means clusters projected with PCA**

![K-Means clusters](assets/kmeans_pca_clusters.png)

**5. Classification performance across models**

![ROC curves](assets/classification_roc_curves.png)

## 🧰 Stack

`Pandas` · `NumPy` · `SciPy` · `Scikit-learn` · `Matplotlib` · `Seaborn`

## ▶️ Quick Start

```bash
python -m pip install pandas numpy scipy scikit-learn matplotlib seaborn jupyter
jupyter notebook Knowledge_Discovery_Final_Project.ipynb
```

Run all cells to generate the dataset and reproduce the analysis. Results may vary between runs.
"# gaza-internet-availability-analytics" 
