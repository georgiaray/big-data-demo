# Environmental Big Data — Demo Notebook

Hands-on demo for the Environmental Big Data lecture. Builds a climate scenario emulator using the IPCC AR6 Scenarios Database.

> This README was written by an LLM and is intended only to get you set up quickly.

## Setup

1. Download the data from [zenodo.org/records/20056332](https://zenodo.org/records/20056332) and save the World-level CSV as `AR6-demo-data.csv` in the root of this directory.

2. Create the environment:
   ```bash
   conda env create -f environment.yml
   conda activate big-data-demo
   ```

3. Open the notebook:
   ```bash
   jupyter notebook demo.ipynb
   ```

Run cells top to bottom.