# brdf-lib

A fork of casselineau's BDRF-lib repository. This repo contains
scripts and libraries to load, analyze and plot Bi-directional
Reflectance Distribution Functions (BRDFs). The original reposity was
the result of the H2020 MSCA IF HEASeRS project
(https://cordis.europa.eu/project/id/101027316).

Dependencies: numpy, scipy, matplotlib. The original repository was
written in Python 2, so the last versions of these libraries that are
compatible with Python 2 have been added to `pyproject.toml`.

## TO-DO

- [ ] Clarify the dependencies and prepare a package with `setuptools`.
- [ ] Test the package on Python 3 with modern versions of the libraries.
- [ ] Include a means to import data from the Cary UMA accessory.
