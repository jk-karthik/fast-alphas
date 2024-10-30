# short-term-price-signal-generation-using-deep-learning

Applying Deep Learning for Short-term price signal (fast alphas) generation on order book data.

## Run the following commands to execute `deepLOB.ipynb`

### Install Conda

```bash
pip install conda
```

### Activate your Conda/Venv Environment

```bash
conda create -n <env_name> python=3.10.15
source activate <env_name>
```

Please note that many crucial packages here like `torch` and `scipy` require a Python version >=3.8 and <3.11.

### Install Requirements into Your Conda/Venv Environment

```bash
pip install -r requirements.txt
```

### Add IPykernel and Start Your Jupyter Notebook

```bash
ipykernel install --name <env_name>
jupyter notebook .
```