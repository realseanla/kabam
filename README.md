# Take-home assignment for Data Scientist position at Kabam

This repository contains my (Sean La) solution to the take home assignment portion of the interview process for the position of Data Scientist at Kabam.

The main solution is in the Jupyter Notebook file `kabam.ipynb`.

I used conda as my main environment manager. 

To replicate my analysis, do the following:
- Run `conda env create -f environment.yml` to create the `kabam` conda environment that I used from the `environment.yml` conda environment configuration file.
- Activate the environment using `conda activate kabam`.
- In the `data` directory, place into it the following:
  - `ka_actions.parquet`,
  - `ka_devices.db`,
  - `ka_users.csv`, and
  - and a subdirectory `processed` which will contain a merged form of the above three files.
- Run the notebook `kabam.ipynb`.
