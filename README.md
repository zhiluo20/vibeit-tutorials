# Vibeit Tutorials

Small examples for the Vibeit Help Center, targeting Vibeit 1.0.1.

1. Open `quickstart.ipynb` and run its code cells in order.
2. Run `hello.py` as a script.
3. Use `analysis.ipynb` to read `data/samples.csv` and create files in `results/`.

Keep the notebook and the `data` folder together. All measurements are synthetic tutorial data. No account, credential, or private research data is included.

Python packages: pandas, matplotlib. The Git and remote tutorials use a separate exercise branch or fork; do not store tokens or private keys in the repository.

## Optional Hugging Face check

After saving your token in Vibeit Settings → Environment and restarting the kernel, run `hf-auth.ipynb` to verify token availability and authorization. Run `hf-download.ipynb` for a small authenticated configuration download. These notebooks do not display your token or account details, and do not test model inference or gated-model access.
