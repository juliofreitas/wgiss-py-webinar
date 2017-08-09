# wgiss-py-webinar
WGISS Tech Webinar - Python for Data Science in Earth Observation Analysis 

## Setup in Ubuntu 16

- Create a new *conda* environment called *geospatial*
```
conda create --name geospatial python=2.7 # The new environment is created at: /home/user/anaconda2/envs/geospatial
```
- View the results by listing all the environments
```
conda info --envs
```
- Activate the *geospatial* environment
```
source activate geospatial
```
- Install a python kernel
```
conda install ipykernel
```
```
- Clone this repository
```
git clone https://github.com/e-sensing/wgiss-py-webinar.git
```
- Start jupyter
```
- Finally, *Jupyter* starts a new browser where you can reach the notebook called ***WGISS_Tech_Webinar.ipynb***
- Once done, to de-activate the geospatial environment run:
```
source deactivate geospatial
```
- To remove the whole geospatial environment
```
conda remove --name geospatial --all
```
