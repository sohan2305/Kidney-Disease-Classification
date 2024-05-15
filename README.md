# Kidney-Disease-Classification


# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/krishnaik06/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```
##### cmd

### dagshub
[dagshub](https://dagshub.com/)

MLflow
Documentation


cmd
mlflow ui
dagshub
dagshub

MLFLOW_TRACKING_URI = https://dag shub.com/sohan2305/Kidney-Disease-Classification.mlflow \
MLFLOW_TRACKING_USERNAME = sohan2305 \
MLFLOW_TRACKING_PASSWORD = 333e06af0de21e16af92092c0b66bd575f8a8642 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI= https://dagshub.com/sohan2305/Kidney-Disease-Classification.mlflow

export MLFLOW_TRACKING_USERNAME= sohan2305

export MLFLOW_TRACKING_PASSWORD=333e06af0de21e16af92092c0b66bd575f8a8642
````


