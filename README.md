# Morse Theory Applied to Neuroscience



## Table of Contents

1. [General Information](#general-information)
2. [Requirements](#requirements)
3. [How to Install](#how-to-install)
4. [Notes](#notes)
5. [Acknowledgements](#acknowledgements)

## General Information

The aim of this project is to support the computations made in a paper where I applied Morse Theory to analyse fMRI brain time series.

## Requirements
Here we will describe the core packages that will be necessary, but due to dependency compatibilities, we have provided a requirements.txt with all packages needed to be installed in a new Anaconda environment.

- Python 3.8+
- pandas
- glob
- os
- memory_profiler
- pathlib
- scipy
  - pearsonr, spearmanr, linalg, correlate
- numpy
  - eig, eigh, nan
- datetime
  - datetime, timedelta
- shutil
- itertools
  - groupby
- seaborn
- math
- scikit-learn
  - LinearRegression, LogisticRegression, StandardScaler, KMeans
- pickle
- matplotlib
  - pyplot

### Detailed List of Packages

- `pandas`
- `glob`
- `os`
- `memory_profiler`
- `pathlib`
- `scipy`
  - `pearsonr`, `spearmanr`, `linalg`, `correlate`
- `numpy`
  - `eig`, `eigh`, `nan`
- `datetime`
  - `datetime`, `timedelta`
- `shutil`
- `itertools`
  - `groupby`
- `seaborn`
- `math`
- `scikit-learn`
  - `LinearRegression`, `LogisticRegression`, `StandardScaler`, `KMeans`
- `pickle`
- `matplotlib`
  - `pyplot`

## How to Install
pip install -r requirements.txt


### Clone the Repository

```pip install -r requirements.txt

git clone https://github.com/username/stock-analysis-tool.git
cd stock-analysis-tool
