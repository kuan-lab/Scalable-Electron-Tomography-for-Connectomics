# README 
This repository contains code and information related to the paper "Scalable electron tomography for connectomics" by Kuan, Phan, et al. Questions about the code and data should be address to the corresponding authors: aaron.kuan@yale.edu, mellisman@ucsd.edu, wei-chung_lee@hms.harvard.edu

## Electron Tomography Data

### 15 Sequential Serial Sections
Dataset shown in Fig. 2 and Extended Data Fig. 5 & 7.

[Full Sampling](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6641498832502784)

[Limited Tilt](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6673863692779520)

[Restored Limited Tilt](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6327975145373696)

### 5x5 Serial Montage
Dataset shown in Extended Data Fig. 6.

[Serial Montage](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5491865976569856)


## Analysis Code

### Tomographic Reconstruction
Tomograms were reconstructed using the [TXBR package](linkinghub.elsevier.com/retrieve/pii/S1047-8477(12)00186-4). See also [Phan et al. 2012](linkinghub.elsevier.com/retrieve/pii/S1047-8477(12)00186-4).

### Fourier Shell Correlation
FSC figures were generated from the jupyter notebook "250614_plot_FSC_figs.ipynb". The FSC calculations were performed using the python script "250613_ab_calc_tomo_FSCs_2d_incr.py", which requires sub-sampled tomograms (e.g. from even-only or odd-only projections) to already be available. 

### Fiducial-Based Resolution Measurements
Figures relating to fiducial (gold bead) measurements were generated from the jupyter notebook "bead_resolution/250826_bead_res.ipynb". Prerequisite calculations were made using the python script "bead_resolution/250826_download_bead_data.py".

