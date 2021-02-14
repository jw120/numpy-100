My solutions from working through the [numpy-100](https://github.com/rougier/numpy-100)
exercises while reading the book [From Python to NumPy](http://www.labri.fr/perso/nrougier/from-python-to-numpy/).

This repository was formed from the original on githut. My solutions are prefixed with `my_`

To use on my mac:

```
# Setup python virtual environment (one-time)
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
# To run jupyter
source .venv/bin/activate
jupyter lab
# To check format
make
```

--- Original README below ---


## 100 numpy exercises

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/rougier/numpy-100/notebooks/100%20Numpy%20exercises.ipynb)

This is a collection of numpy exercises from numpy mailing list, stack overflow, and numpy documentation. I've also created some problems myself to reach the 100 limit. The goal of this collection is to offer a quick reference for both old and new users but also to provide a set of exercises for those who teach. For extended exercises, make sure to read [From Python to NumPy](http://www.labri.fr/perso/nrougier/from-python-to-numpy/).

→ [Test them on Binder](http://mybinder.org:/repo/rougier/numpy-100/notebooks/100_Numpy_exercises.ipynb)
→ [Read them on GitHub](100_Numpy_exercises.md)

Note: markdown and ipython notebook are created programmatically from the source data in `source/exercises.ktx`.
To modify the content of these files, please change the text in the source and run the `generators.py` module with a python
interpreter with the libraries under `requirements.txt` installed.

The keyed text format (`ktx`) is a minimal human readable key-values to store text (markdown or others) indexed by keys.

This work is licensed under the MIT license.
[![DOI](https://zenodo.org/badge/10173/rougier/numpy-100.svg)](https://zenodo.org/badge/latestdoi/10173/rougier/numpy-100)
