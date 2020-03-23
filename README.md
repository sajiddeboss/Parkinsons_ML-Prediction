# Parkinsons_ML-Prediction
Detecting Parkinsons with ML
We'll use the data from UC Irvine's amazing dataset repository, specifically the Parkinsons ML database.

There are two datasets within this. The first is in the root folder (parkinsons.data which is included here too) and can be used to detect Parkinsons. The second is within the telemonitoring/ directory and contains UDPR scores for us to predict.

Approach
Parkinsons detection is likely best done with an XGBoost since outputs are 0 or 1 and it seems mostly linear.

The UDPR is very hard to fine tune with XGBoost. 

Both approaches are provided in the Jupyter notebook for this repo (Train.ipynb). Run using jupyter notebook from this repo's root folder in the terminal.

You can find more info on the datasets in UCI's database. (info for Parkinsons detection) (info for UDPR)

Requirements:
Python 3, XGBoost, sklearn, Pandas, NumPy 

I don't own this dataset, it's provided in the link earlier.

Citations for the datasets used:

'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', 
Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. 
BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)
A Tsanas, MA Little, PE McSharry, LO Ramig (2009)
'Accurate telemonitoring of Parkinson.s disease progression by non-invasive speech tests',
IEEE Transactions on Biomedical Engineering (to appear).


If you use this repo please cite it:

Priansh Shah. (2018, April 4). Detecting Parkinsons with AI (Version DOI). Zenodo. 
http://doi.org/10.5281/zenodo.1211859
Bibtex:

@misc{priansh_shah_2018_1211859,
  author       = {Priansh Shah},
  title        = {Detecting Parkinsons with AI},
  month        = apr,
  year         = 2018,
  doi          = {10.5281/zenodo.1211859},
  url          = {https://doi.org/10.5281/zenodo.1211859}
}
