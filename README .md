# Study-held-out validation of machine-learning models for biomass gasification

Code and results for the manuscript "Study-Held-Out Validation of Machine-Learning Models for Biomass Gasification: Random Cross-Validation Overstates Accuracy and Prediction Intervals Remain Wide" (Priom Dey, Avro Talukder, Yuvraj Roy; Department of Chemistry, Shahjalal University of Science and Technology).

Zenodo archive: https://doi.org/10.5281/zenodo.23645766

## Data
The experimental data are **not** included. They are the public compilation of Ascher et al. (Bioresour. Technol. 364, 128062, 2022), downloaded at run time from the original repository (pinned commit b4b75058e64c799fddd0c334d68041440966c1ef). Please cite that work and check its repository for terms of use.

## Run
Open `biomass_gasification_study_held_out.ipynb` in Google Colab and run all cells (about 14 minutes). Outputs appear in `gasification_results/`.

## Files (all in the top-level folder)
- `biomass_gasification_study_held_out.ipynb` – analysis notebook
- `*.csv`, `summary.json`, `fig1`–`fig4` `.png` – results of the reported run (scikit-learn 1.6.1, seed 42)
- `paper.tex`, `paper.pdf` – manuscript
- `make_paper_gas.py` – rebuilds `paper.tex` from the result files: `python make_paper_gas.py --res . --out paper_out`
- `requirements.txt` – Python packages
