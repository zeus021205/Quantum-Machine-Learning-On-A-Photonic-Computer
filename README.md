# Upload bundle: QNN Iris + QGenAI BAS

This bundle contains the datasets, training notebooks, plot notebooks, histories, CSV tables, and generated figures used for the current QNN and QGenAI experiments.

## Main datasets

- `datasets/iris_binary_qnn/`: Iris classes 0 and 1 from `sklearn.datasets.load_iris`, split with `random_state=42`, scaled to `[0, 2*pi]` for angle/phase encoding.
- `datasets/bas_2x2_qgenai/`: BAS 2x2 target distribution, uniform over 6 valid Bars-and-Stripes bitstrings.

## Main notebooks

- `notebooks/qnn_iris/`: QNN training notebooks for MZI, CNOT-chain, and Classical baselines from 1 to 5 layers.
- `notebooks/qgenai_bas/`: QGenAI BAS Born Machine notebook comparing MZI, repeated CNOT, and Classical MLP.
- `notebooks/plots/`: Combined plotting notebooks for QNN and QGenAI.

## Figures

Both PNG and PDF versions are included. Prefer PDF in LaTeX when possible because it is vector and keeps text sharp.
