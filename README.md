This folder contains scripts and outputs for the greenocean group's Global Carbon Budget submission for the year 2024.

Contents:

- `./submissionData2024`: contains data (not available on github), we are using model version RIV12
- `GCB2024_ocean_model_protocol.pdf`: protocol as received from J. Hauck
- `./scripts` contains scripts that produce output, with the batch submission file `runGCB.bsub`, that can be run using `sbatch < runGCB.bsub` 
    - Note: currently `runGCB.bsub` requires some python packages that are contained in an environment called swamp2 (notably arrow), if you are running this in the future and it's not working, check imports.
    - scripts used to make each variable are documented in SPREADSHEET (see References)
- `./notebooks` contains notebooks for visualizing outputs


References:
- The following notion page documents the code, forcing, run id's, etc: [NOTION](https://nettle-pajama-b85.notion.site/GCB-2024-run-specifications-and-monitor-setup-ead416b3867841cf9bb81b695b1c7a5d?pvs=74)
- The following google spreadsheet, editable by TJŠJ and viewable by all, contains a list of all variables required by the GCB, what the output files are, where they are made, etc: [SPREADSHEET](https://docs.google.com/spreadsheets/d/1EUf1SV671k1wtSX4ccQ3CnOmnQMrtfcvsIs1SSyOzh4/edit?usp=sharing)
- The following notebook contains a visualization of the output of this year's model runs and a comparison with last year's, where applicable:
[NOTEBOOK](https://github.com/tjarnikova/GCB2024/blob/main/notebooks/visualiseAllGCBOutputs.ipynb)


## TODOS/ not done yet for 2024

- `./ModelCodeAndRunFiles` contains the archive of the model Fortran code and associated run files 
