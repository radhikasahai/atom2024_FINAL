# atom2024
MSSE Capstone 2024 - ATOM NEK 3 and NEK 5

Radhika Sahai


### Environment Variables


This repository has 2024 final Capstone project for Berkeley MSSE. This contains models that predict the bingind class for NEK3 and NEK5. In partnership with  Open Data and Models group at the Accelerating Therapeutics for Opportunities in Medicine (ATOM) Consortium. 
The data is provided by Chembl, but it is not included here as an extra precaution.

Installation
To set up this project locally, follow the steps below:

git clone https://github.com/radhikasahai/atom2024_FINAL.git

To install and activate the conda virtual environment:

install conda
conda env create -f environment.yml

conda deactivate
Directory
Utility functions used throughout this project are located in the root directory. These are Python scripts including:

utils.py: for molecular normalization
RF_Utils.py: building RF models and evaulating metrics
split_data.py: for creating random splits
VisUtils.py: plotting functions

Contact
Radhika Sahai: radhikasahai786@gmail.com