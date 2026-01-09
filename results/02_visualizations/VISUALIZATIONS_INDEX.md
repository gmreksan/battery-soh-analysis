# Visualizations Index
## Battery SOH Analysis Project

### Available Visualizations

All visualizations are generated from the `visualization.py` module and saved as high-resolution PNG files (300 DPI).

---

## 1. EDA VISUALIZATIONS (from figures/eda/)

### 1.1 SOH Trend (Figure 1)
**File**: `fig_1_soh_trend.png`
**Function**: `plot_soh_trend()`
**Description**:
- Line plot showing SOH decline over checkups for both cells
- AC01 (blue #2E86AB) and AC02 (magenta #A23B72)
- 80% EOL threshold (red dashed line)
- 85% Warning level (orange dashed line)
- Markers: circles, linewidth: 2
- Size: 7x5 inches

### 1.2 Capacity Fade (Figure 2)
**File**: `fig_2_capacity_fade.png`
**Function**: `plot_capacity_fade()`
**Description**:
- Discharge capacity (mAh) vs checkup number
- Square markers for both cells
- Shows absolute capacity decline over time
- Same color scheme as SOH trend
- Size: 7x5 inches

### 1.3 SOH Distribution (Figure 3)
**File**: `fig_3_soh_distribution.png`
**Function**: `plot_soh_distribution()`
**Description**:
- Histogram of SOH values (15 bins)
- Steelblue color with black edges
- 80% EOL threshold line (red dashed)
- Mean SOH line (green dashed)
- Shows overall health distribution
- Size: 7x5 inches

### 1.4 Degradation Rate Analysis (Figure 4)
**File**: `fig_4_degradation_rate.png`
**Function**: `plot_degradation_rate()`
**Description**:
- Scatter plot with linear regression lines
- Shows degradation rate per checkup
- Includes prediction lines extending 5 checkups
- Displays slope (% per checkup) in legend
- 80% EOL threshold line
- Prints degradation statistics to console
- Size: 7x5 inches

---

## 2. MODELING VISUALIZATIONS (from figures/modeling/)

### 2.1 Predicted vs Actual SOH
**File**: `predicted_vs_actual_soh.png`
**Function**: `plot_predicted_vs_actual()`
**Description**:
- Scatter plot comparing predictions to actual values
- Perfect prediction line (black dashed, y=x)
- Alpha: 0.7, marker size: 80
- Size: 10x6 inches

### 2.2 Model Performance Comparison
**File**: `model_performance_comparison.png`
**Function**: `plot_model_performance_comparison()`
**Description**:
- Three-panel bar chart (1 row, 3 columns)
- Panel 1: MAE - skyblue
- Panel 2: RMSE - lightgreen  
- Panel 3: R2 Score - salmon
- Size: 15x5 inches

---

**Generated**: 2026-01-09 06:34:15
**Module**: visualization.py  
**Total Functions**: 8 main functions
