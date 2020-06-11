This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

Since we are using katacoda build env for this tutorial, we need wget tool so that we can install miniconda environment.

`apt-get update; apt-get install wget`{{execute}}

Get Miniconda Installer

`wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O miniconda.sh`{{execute}}

Install miniconda

`bash ./miniconda.sh -b -p miniconda3`{{execute}}

Source miniconda environment

`source ./miniconda3/etc/profile.d/conda.sh`{{execute}}

Activate conda base environment

`conda activate base`{{execute}}

