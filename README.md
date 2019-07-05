# An introduction presentation in Jupyter notebook to Machine Learning

Using python 3.6, sklearn and pandas.

## Running the notebook:

If anaconda isn't already installed, please see https://www.anaconda.com/distribution/#download-section for installation instructions.

To create an environment and run the notebook:
conda env create -f environment.yml -n intro

conda activate intro
jupyter notebook

To close the notebook:
Ctrl + C to kill the kernel
conda deactivate

To convert to presentation:
jupyter nbconvert Presentation.ipynb --to slides --post serve
