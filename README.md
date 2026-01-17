# Brain Age Prediction using Stacking Ensemble

MRI-based brain age estimation using region-wise stacking ensemble method.

## 📊 Results
- **Baseline (Regional Mean GMV):** MAE = 6.83 years, r = 0.853
- **Stacking Ensemble (L0+L1):** MAE = 5.73 years, r = 0.899
- **Improvement:** 16.1% (1.10 years MAE reduction)

## 🧠 Methods
- **Dataset:** IXI (N=563)
- **Atlases:** Schaefer-800 + Brainnetome-36 + Cerebellar-34
- **Models:** ElasticNet (Level-0 + Level-1)

## 📁 Files
- `Brain Age Estimation Using IXI Data.ipynb` - Complete analysis pipeline
- `summary_figure.png` - Main results visualization
- `model_comparison.png` - Baseline vs SE comparison
- `error_analysis.png` - Error distribution & residuals
- `region_importance.png` - Top predictive brain regions
- `final_results_table.csv` - Performance metrics

## 📚 Reference
Based on: More et al. (2025) "Region-wise stacking ensembles for estimating brain-age using structural MRI"

## 🎓 Author
Fatma Karateke
