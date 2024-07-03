![Version](https://img.shields.io/github/v/tag/tfp-photonics/treams)
[![PyPI](https://img.shields.io/pypi/v/treams)](https://pypi.org/project/treams)
![License](https://img.shields.io/github/license/tfp-photonics/treams)
![build](https://github.com/tfp-photonics/treams/actions/workflows/build.yml/badge.svg)
[![docs](https://github.com/tfp-photonics/treams/actions/workflows/docs.yml/badge.svg)](https://tfp-photonics.github.io/treams)
![doctests](https://github.com/tfp-photonics/treams/actions/workflows/doctests.yml/badge.svg)
![tests](https://github.com/tfp-photonics/treams/actions/workflows/tests.yml/badge.svg)
[![coverage](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftfp-photonics%2Ftreams%2Fhtmlcov%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/tfp-photonics/treams/blob/htmlcov/index.html)

# treams

The package `treams` provides a framework to simplify computations of the
electromagnetic scattering of waves at finite and at periodic arrangements of particles
based on the T-matrix method.

## Installation

### Installation using pip

To install the package with pip, use

```sh
pip install treams
```

If you're using the system wide installed version of python, you might consider the
``--user`` option.

## Documentation

The documentation can be found at https://tfp-photonics.github.io/treams.

## Publications

When using this code please cite:

[D. Beutel, I. Fernandez-Corbaton, and C. Rockstuhl, treams - A T-matrix scattering code for nanophotonic computations, arXiv (preprint), 2309.03182 (2023).](https://doi.org/10.48550/arXiv.2309.03182)

Other relevant publications are
* [D. Beutel, I. Fernandez-Corbaton, and C. Rockstuhl, Unified Lattice Sums Accommodating Multiple Sublattices for Solutions of the Helmholtz Equation in Two and Three Dimensions, Phys. Rev. A 107, 013508 (2023).](https://doi.org/10.1103/PhysRevA.107.013508)
* [D. Beutel, P. Scott, M. Wegener, C. Rockstuhl, and I. Fernandez-Corbaton, Enhancing the Optical Rotation of Chiral Molecules Using Helicity Preserving All-Dielectric Metasurfaces, Appl. Phys. Lett. 118, 221108 (2021).](https://doi.org/10.1063/5.0050411)
* [D. Beutel, A. Groner, C. Rockstuhl, C. Rockstuhl, and I. Fernandez-Corbaton, Efficient Simulation of Biperiodic, Layered Structures Based on the T-Matrix Method, J. Opt. Soc. Am. B, JOSAB 38, 1782 (2021).](https://doi.org/10.1364/JOSAB.419645)


## Features

* [x] T-matrix calculations using a spherical or cylindrical wave basis set
* [x] Calculations in helicity and parity (TE/TM) basis
* [x] Scattering from clusters of particles
* [x] Scattering from particles and clusters arranged in 3d-, 2d-, and 1d-lattices
* [x] Calculation of light propagation in stratified media
* [x] Band calculation in crystal structures
