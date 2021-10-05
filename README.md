# testes_tecnicos
Todos os notebooks devem ser reproduzidos utilizando o ambiente do arquivo "ambiente.yml"
Caso não seja possível utiliza-lo, abaixo está a transcrição dos comandos inseridos no Anaconda prompt para criar esse ambiente no Windows 10 64-bit:


conda create -n ambiente python=3.8.10 ipython 

conda activate ambiente

conda install -c conda-forge jupyterlab=3.0.14

conda config --env --add channels conda-forge

conda config --env --set channel_priority strict

conda install -c conda-forge geopandas=0.8.1

conda install -c conda-forge xarray dask netCDF4 bottleneck cfgrib

pip install joblib

pip install requests

pip install requests-futures

pip install tqdm

pip install plotly

pip install seaborn

pip install salem

pip install descartes

pip install wget

conda install rasterio

conda install rioxarray

