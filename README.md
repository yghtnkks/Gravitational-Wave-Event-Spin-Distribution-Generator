# Gravitational-Wave-Event-Spin-Distribution-Generator
This code is utilised to create probability distributions to GW events utilising spin information. More information on the theoretical background is presented in the research. Please refer to the appendix or README file for configuration before running the code. 


The code best runs in a virtual environment. Utilising pyenv, create a virtual environment and install the modules pesummary, h5py, p_astro, pycbc, and gwpy. For more information on pyenv configuration, https://lscsoft.docs.ligo.org/pesummary/reference/virtual_environment.html

Before running the code, also download '.csv' file for gravitational wave events and put it into the directory you want to work. For obtaining .h5 files, either utilise pesummary( refer to: https://lscsoft.docs.ligo.org/pesummary/latest/gw/fetch.html) or manually download them. The process of downloading the wave events manually is mentioned in the appendix of the paper. 

It is highly suggested for the code to be opened on a code editor such as VSCode with Jupyter Notebook configured. 
