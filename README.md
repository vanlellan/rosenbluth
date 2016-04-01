This is the Python code used in the reanalysis of Rosenbluth measurements of the proton form factors described in [arXiv:1603.06920](http://arxiv.org/abs/1603.06920) (please consider citing this paper if you use the code). The **radcorr.py** library may be useful for calculating radiative corrections in single-arm measurements of unpolarized elastic electron-proton scattering.

![Fig. 2 from arXiv:1603.06920](fig2.png)

## Dependencies

The standard Python packages **scipy**, **numpy**, **pandas**, and **matplotlib** are required.

## Source distribution

The source distribution includes the following files:

* DOCUMENTATION
  * **README.md** (this markdown file)
  * **LICENSE** (the MIT license)
  * **data_input.pdf** (input data in a human-readable format)
* SOURCE CODE
  * **reanalysis.py** (main analysis routine)
  * **radcorr.py** (Python library to account for radiative corrections)
  * **fig1.py** (script to plot Fig. 1 of the paper)
  * **fig2.py** (script to plot Fig. 2 of the paper)
* INPUT DATA
  * **data_input.csv** (data from the measurements reanalyzed)
  * **data_esepp.csv** (data from [ESEPP](https://github.com/gramolin/esepp/) needed for Fig. 1)
  * **data_unpolarized.csv** (results of the original measurements needed for Fig. 2)
  * **data_polarized.csv** (results of the polarized measurements needed for Fig. 2)
* OUTPUT FILES
  * **results_fit.csv** (the best-fit parameters and the covariance matrix found)
  * **results_table.csv** (reanalysis results shown in Table I of the paper)
  * **fig1.pdf** and **fig1.png** (Fig. 1 of the paper in the pdf and png formats)
  * **fig2.pdf** and **fig2.png** (Fig. 2 of the paper in the pdf and png formats)
