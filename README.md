# About

*This is a fork of AliPy to GitHub to make my Docker install work. See link below to original*

This is a python package to quickly, automatically, and robustly identify geometrical transforms between optical astronomical images, using only field stars. The images can have different pixel sizes, orientations, pointings and filters.

http://obswww.unige.ch/~tewes/alipy/


# Installation

Quick :
`python setup.py install`

To create a source distribution :
`python setup.py sdist`

More info :
http://docs.python.org/distutils/

# Dependence

sextractor
The executable must be available as sex, not as sextractor. Make an alias if required.

For Ubuntu

`sudo apt install sextractor`
