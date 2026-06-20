# TOI3235b-JWST-transmission

Notebooks to generate figures for:

**"JWST Transmission Spectroscopy of TOI-3235 b: Constraints on Giant Planet Formation around M Dwarfs amid Stellar Contamination"**

The data products and models required to run these notebooks are archived on Zenodo:

[10.5281/zenodo.20738525](https://doi.org/10.5281/zenodo.20738525)

The original JWST observations are available from MAST:

[10.17909/02a7-ck05](https://doi.org/10.17909/02a7-ck05)

## Contents

- `transmission_figures.ipynb`: Generates the transmission spectrum retrieval figures.
- `emission_figures.ipynb`: Generates the synthetic emission spectra retrieval figures.
- `VULCAN_chemeq_figures.ipynb`: Generates chemical-equilibrium comparison figures.
- `paper_figs/`: Generated manuscript figures.

## Usage

To reproduce the figures, download the Zenodo archive, then run the notebooks in this repository. Users may need to update the data paths in the notebooks.

The notebooks require the following external Python packages:

- `numpy`
- `matplotlib`
- `pandas`
- `corner`
- `exocomp`

## License

The notebooks in this repository are released under the MIT License. See `LICENSE.md`.

The data products and model outputs required to run the notebooks are archived separately on Zenodo and released under the Creative Commons Attribution 4.0 International License.
