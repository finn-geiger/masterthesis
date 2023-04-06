# Create Environment for project
The work within this repository was done using a conda environment. 
To repreduce the code, two options are available to install the required packages.

## Option 1 - Using a conda environment
In order to create a conda environment conda needs to be installed. 

For this visit https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

Once conda is installed, the following command creates desired environment:

conda create --name MyEnv --file conda_env_requirements.txt

The envionment can be activated using:

conda activate MyEnv

## Option 2 - Using the python package installer (pip)
The second option is using pip to create a virtual environment. 
For this, the following commands must be used:

python3 -m venv env

source env/bin/activate

pip install -r pip_requirements.txt

### Resources used for this:
https://stackoverflow.com/questions/50777849/from-conda-create-requirements-txt-for-pip3
