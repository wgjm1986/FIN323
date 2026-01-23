This repository contains course materials for FIN 323 taught by William Mann at Emory University. 
See the [landing page](https://wgmann.github.io/FIN323) for more information.
To use this repo:

    git clone https://github.com/wgmann/FIN323
    cd FIN323
    conda env create -f environment.yml
    conda activate FIN323
    python -m ipykernel install --user --name FIN323 --display-name "FIN323 (conda)"
    cp .env.example .env

...add WRDS username and FRED API to .env, then

    jupyter notebook

...and navigate to any notebook file to run it.
