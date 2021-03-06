# Probabilistic Numerics in Python

[![Build Status](https://travis-ci.org/probabilistic-numerics/probnum.svg?branch=master)](https://travis-ci.org/probabilistic-numerics/probnum)
[![Coverage Status](http://codecov.io/github/probabilistic-numerics/probnum/coverage.svg?branch=master)](http://codecov.io/github/probabilistic-numerics/probnum?branch=master)
<br>

<a href="https://probabilistic-numerics.github.io/probnum/intro.html"><img align="left" src="https://raw.githubusercontent.com/probabilistic-numerics/probnum/master/docs/source/img/pn_logo.png" alt="probabilistic numerics" width="128" style="padding-right: 10px; padding left: 10px;" title="Probabilistic Numerics on GitHub"/></a> 
[Probabilistic Numerics](https://doi.org/10.1098/rspa.2015.0142) (PN) interprets classic numerical routines as 
_inference procedures_ by taking a probabilistic viewpoint. This allows principled treatment of _uncertainty arising 
from finite computational resources_. The vision of probabilistic numerics is to provide well-calibrated probability 
measures over the output of a numerical routine, which then can be propagated along the chain of computation.

This repository aims to implement methods from PN in Python 3 and to provide a common interface for them. This is
currently a work in progress, therefore interfaces are subject to change.

## Installation and Documentation
You can install this Python 3 package using `pip` (or `pip3`):
```bash
pip install git+https://github.com/probabilistic-numerics/probnum.git
```
Alternatively you can clone this repository with
```bash
git clone https://github.com/probabilistic-numerics/probnum
pip install probnum/.
```
For tips on getting started and how to use this package please refer to the
[documentation](https://probabilistic-numerics.github.io/probnum/modules.html).

## Examples
Examples of how to use this repository are available in the 
[examples section](https://probabilistic-numerics.github.io/probnum/notebooks/examples.html) of the documentation. It 
contains Jupyter notebooks illustrating the basic usage of implemented probabilistic numerics routines.

## Package Development
This repository is currently under development and benefits from contribution to the code, examples or documentation.
Please refer to the [contribution guide](https://probabilistic-numerics.github.io/probnum/contributing.html) before 
making a pull request.

A list of core contributors to ProbNum can be found 
[here](https://probabilistic-numerics.github.io/probnum/contributing.html#code-contributors).

## License and Contact
This work is released under the [MIT License](https://github.com/probabilistic-numerics/probnum/blob/master/LICENSE.txt).

Please submit an [issue on GitHub](https://github.com/probabilistic-numerics/probnum/issues/new) to report bugs or 
request changes.
