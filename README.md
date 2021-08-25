# PATH SCRIPTS

> This repo contains some (custom) scripts that I like to have on my path to speed of my daily tasks.

## `setup-jupyter`

This script creates the virtual environment for the project and adds the venv
as a kernel to the jupyter notebook.
It also creates a 'start' script to activate the virtual environment and
start the notebook server.

### Usage:

```
usage: setup-jupyter [-h] [--jupyter-bin JUPYTER_BIN] [--venv VENV] [--python-interpreter PYTHON_INTERPRETER] project-name path

Quickly setup a jupyternotebook in a venv with vim binds

positional arguments:
  project-name          the name of the project
  path                  the path to create the setup in

optional arguments:
  -h, --help            show this help message and exit
  --jupyter-bin JUPYTER_BIN
                        the path that contains the jupyter executable
  --venv VENV           the name of the venv
  --python-interpreter PYTHON_INTERPRETER
                        the python interpreter to use (default: python3)
```
