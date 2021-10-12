# RCSB Python DSSP Utilities

[![Build Status](https://dev.azure.com/rcsb/RCSB%20PDB%20Python%20Projects/_apis/build/status/rcsb.py-rcsb_utils_dssp?branchName=master)](https://dev.azure.com/rcsb/RCSB%20PDB%20Python%20Projects/_build/latest?definitionId=&branchName=master)

## Introduction

This module contains utility methods for calculating DSSP secondary structure entries for models in the RCSB PDB archive.

### Installation

Download the library source software from the project repository:

```bash

git clone --recurse-submodules https://github.com/rcsb/py-rcsb_utils_dssp.git

```

**Important:** Setup will require an up-to-date version of [cmake](https://cmake.org/install/) to be installed on the machine and the executable to be in the system's PATH.

Optionally, run test suite (Python versions 3.9) using
[setuptools](https://setuptools.readthedocs.io/en/latest/) or
[tox](http://tox.readthedocs.io/en/latest/example/platform.html):

```bash
python setup.py test

or simply run

tox
```

Installation is via the program [pip](https://pypi.python.org/pypi/pip).

```bash
pip install rcsb.utils.dssp

or for the local repository:

pip install .
```

## References
* DSSP 4.0. Maarten L. Hekkelman, et al. https://github.com/PDB-REDO/dssp
* libcifpp. Maarten L. Hekkelman, et al. https://github.com/PDB-REDO/libcifpp
