# Eccentric Binary Neutron Star Search Prospects for Cosmic Explorer
**Amber K. Lenon<sup>1</sup>, Duncan A. Brown<sup>1</sup>, Alexander H. Nitz<sup>2,3</sup>**

 <sub>1. Department of Physics, Syracuse University, Syracuse, NY 13244, USA</sub>

 <sub>2. [Albert-Einstein-Institut, Max-Planck-Institut for Gravitationsphysik, D-30167 Hannover, Germany](http://www.aei.mpg.de/obs-rel-cos)</sub>  

 <sub>3. Leibniz Universitat Hannover, D-30167 Hannover, Germany</sub>  


## License ##
![Creative Commons License](https://i.creativecommons.org/l/by-sa/3.0/us/88x31.png "Creative Commons License")

This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 United States License](http://creativecommons.org/licenses/by-sa/3.0/us/).

## Introduction ##

This notebook is a companion to Lenon, Brown and Nitz (2021) posted at [arXiv:2103.14088](https://arxiv.org/abs/2103.14088). In this paper we determine the ability of Cosmic Explorer to detect eccentric binary neutron stars and to measure their eccentricity. This notebook demonstrates how the figures in the paper were generated.

We encourage use of these data in derivative works. If you use the material provided here, please cite the paper using the reference:

```
@article{,
      author         = "Lenon, Amber K. and Brown, Duncan A. and Nitz, Alexander H.",
      title          = "{Eccentric Binary Neutron Star Search Prospects for Cosmic Explorer}",
      year           = "2021",
      eprint         = "2103.14088",
      archivePrefix  = "arXiv",
      primaryClass   = "astro-ph.HE",
      SLACcitation   = "%%CITATION = ARXIV:2103.14088;%%"
}
```

## Running this notebook in a Docker container ##

This notebook can be run from a PyCBC Docker container, or a machine with PyCBC installed. Instructions for [downloading the docker container](http://gwastro.github.io/pycbc/latest/html/docker.html) are available from the [PyCBC home page.](https://pycbc.org/) To start a container with instance of Jupyter notebook, run the commands

```sh
docker pull pycbc/pycbc-el7:v1.18.0
docker run -it -p 8888:8888 --name pycbc_notebook pycbc/pycbc-el7:v1.18.0 /bin/bash -l
```
Once the container has started, this git repository can be downloaded with the command:
```sh
git clone https://github.com/gwastro/cosmic-explorer-bns-eccentricity.git
```
The notebook server can be started inside the container with the command:
```sh
jupyter notebook --ip 0.0.0.0 --no-browser
```
You can then connect to the notebook server at the URL printed by ``jupyter``. Navigate to the directory `cosmic-explorer-bns-eccentricity` in the cloned git repository and open [data_release.ipynb](https://github.com/gwastro/cosmic-explorer-bns-eccentricity/blob/master/data-release.ipynb), the notebook that demonstartes use of these results.

## Acknowledgments ##

We acknowledge the Max Planck Gesellschaft for support and the Atlas cluster computing team at AEI Hannover. DAB thanks National Science Foundation Grants~PHY-1707954 and PHY-2011655 for support. AL thanks National Science Foundation Grant AST-1559694 for support.
