# Asset-Azure-Deployment

## Introduction

This repository is the base repository that contains the files required to deploy the asset solution on Azure, which are as follows:

- File 1: asset.yml
- File 2: asset.dev.solution.yml

</br>

```bash
.github
└── workflows
    └── asset.yml
config
└── asset.dev.solution.yaml
```
## Files

- `asset.yml file`: The required file for deploying asset. It contains all the necessary actions for deploying the solution. From this file, calls are made to actions that are developed in the `Cosmo-Tech/babylon-action@asset` repository. The actions depend on the solution  (supply asset brewery...)

- `asset.dev.solution.yaml`: This file contains the structure of our solution. It varies for each solution, and this file is valid only for asset.

