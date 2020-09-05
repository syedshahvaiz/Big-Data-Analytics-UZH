ReadMe File for Business Analytics Project

Do not start the Jupyter notebook until you have completed Step 1:

## Step 1: Installing Dependencies

- Install the Anaconda (5.3) distribution from https://www.anaconda.com/download/

- Go to Anaconda prompt
  - Create a new environment based on standard anaconda packages using `conda create -n BA anaconda`
  - Activate the enviornment: `conda activate BA`
  - Install Yellowbricks package: `conda install -c districtdatalabs yellowbrick`
  - Install the remaining required packages in the environment using `pip install -r requirements.txt`
  - Install ipykernel: `conda install -c anaconda ipykernel`
  - Type 'python -m ipykernel install --user --name=BA' (This will allow Jupyter to access this enviornment)

## Step 2: Jupyter configuration
- Choose the 'BA' kernel in the kernel section to run the file. 

If the kernel installation fails then you will have to install the missing packages manually. 

Packages which might be missing are:

1. scikit-learn: (conda install scikit-learn)
2. yellowbrick: (conda install -c districtdatalabs yellowbrick)
3. plotly: (conda install -c plotly plotly)
4. seaborn: (conda install -c anaconda seaborn)
5. keras: (conda install -c conda-forge keras)

Once these packages are installed in your machine then you will be able to run the notebook and reproduce the results





