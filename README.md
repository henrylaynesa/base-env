# base-env
Base conda environment for data analysis. I've noticed I install the same packages when I start doing another project so I've decided to just push a base conda environment for future reference.

## Setup
Run
```s
conda env create -f base-env.yml
```
if you don't have it yet. You can alternatively use requirements.txt.

If base-env is already added to your device, run
```
conda create --name new-env --clone base-env
```
and replace new-env with the new environment name.

This should save me some time searching and installing base packages.
