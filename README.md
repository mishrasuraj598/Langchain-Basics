# Langchain basics notebooks

## Creating a new python environment

```bash
conda create -n langchain-env python=3.10 -y        # Create a new conda environment
conda activate langchain-env                        # Activate the conda environment
pip install -r requirements.txt                 # Install the required packages
conda install pip                               # Install pip in the conda environment
pip list --format=freeze > requirements.txt     # Save the installed packages to requirements.txt
conda deactivate                                # Deactivate the conda environment
```
