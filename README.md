# scRNA_ipynb
ipynb collection for scRNA-seq analysis

# env

I use [mambaforge](https://github.com/conda-forge/miniforge) for virtual env for python and R

## installation of mamba forge(linux)

Download the installer using curl or wget or your favorite program download files and run the script. For eg:

```bash
wget "https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-$(uname)-$(uname -m).sh"
bash Mambaforge-$(uname)-$(uname -m).sh
```

## create virtual env

```bash
mamba env create -n scRNA -f environment.yml
```

## Activate env

```bash
mamba activate scRNA
```

## Run jupyter-lab

```bash
$jupyter-lab
```
