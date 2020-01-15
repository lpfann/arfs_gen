# All Relevant Feature Selection Generator Library (ARFS-Gen)

This repository contains a python library to generate synthetic (toy) data for use in research papers when evaluating all relevant feature selection e.g.  used in [fri](https://github.com/lpfann/fri).

It allows creating datasets with a specified number of strongly and weakly relevant features as well as random noise features.

In the newest revision it also includes methods which generate data with privileged information.

It works by utilizing existing methods from `numpy` and `scikit-learn`.


# Development
For dependency management we use the newly released [poetry](https://python-poetry.org/) tool.

If you have `poetry` installed, use
```shell
$ poetry install
```  
inside the project folder to create a new `venv` and to install all dependencies.
To enter the newly created `venv` use 
```shell 
$ poetry env
```
to open a new shell inside.
Or alternatively run commands inside the `venv` with `poetry run ...`.

## Test
Test it by running `poetry run pytest`.
