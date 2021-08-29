# Setup conda

```sh
conda create -n python-setup
conda activate python-setup
conda install python

conda search -c <channel> <lib>

conda env list
conda list # libraries
conda env export > conda-env.yaml
conda env create -f conda-env.yaml

conda deactivate
conda env remove -n python-setup
conda clean --all
```

based on https://whiteboxml.com/blog/the-definitive-guide-to-python-virtual-environments-with-conda
