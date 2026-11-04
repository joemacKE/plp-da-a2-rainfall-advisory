# PLP Data Analysis Assignment 2: Rainfall Advisory

This project cleans monthly rainfall readings for Nairobi, Nakuru, Kisumu, Mombasa and Machakos, analyses county and monthly rainfall patterns with NumPy, and exports a five-county summary to CSV.

## How to run

1. Clone or download this repository and install the dependencies with `pip install -r requirements.txt`.
2. Open `rainfall_analysis.ipynb` in Jupyter Notebook, JupyterLab or Google Colab.
3. Restart the kernel and run every cell from top to bottom; the notebook creates `rainfall_summary.csv` in its working directory.

## Planting advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April-May as their highest-rainfall consecutive two-month window in this dataset.
- Machakos has November-December as its highest-rainfall consecutive two-month window after two missing readings are imputed.
- Treat these windows as planning signals rather than guarantees, and confirm soil moisture, local conditions and current seasonal forecasts before advising farmers to plant.

## Files

- `rainfall_analysis.ipynb` — cleaning, NumPy analysis, advisory and data-quality notes.
- `rainfall_summary.csv` — one summary record for each of the five counties.
- `requirements.txt` — Python library dependencies.
