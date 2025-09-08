# 4th-down-models

### Env Commands

Create the conda env
```
conda env create -f env.yml
```

Actviate conda env

```
conda activate 4thdown
```

Create a Jupyter Kernel for the env
```
python -m ipykernel install --user --name 4thdown --display-name "4th Down"
```

Updating the conda env
```
conda env update -f env.yml --prune
```