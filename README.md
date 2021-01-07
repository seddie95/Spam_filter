
## Prerequisites
- Install Anaconda
- Open terminal with administration privileges 
- Create environment with requirements


### Installing Anaconda
Anaconda is available for Windows, Linux and MacOS, it can be installed [here.](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)


### Creating Conda Environment and Installing Dependencies
Ensure that for Windows you open the Anaconda prompt or terminal using administrative privileges 
or use sudo for Linux and MacOS.


1. Create the conda environment using the environment.yml file
    ```
    conda env create -f environment.yml
    ```

2. Once the environment has been created successfully with all dependencies  activate the environment.
    ```
    conda activate spam_emails
    ```

3. Download the spacy English language files
    ```
    python -m spacy download en
    ```

## Running Python Notebooks

Open jupyter notebooks to view .ipynb files

```
jupyter notebook
```