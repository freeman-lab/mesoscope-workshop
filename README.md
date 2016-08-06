# mesoscope-workshop

> notebooks for workshop on analyzing data from the two-photon mesoscope

This repository contains a collection of Jupyter notebooks, alongside sample data, for demonstrating some basic analyses of [`mesoscope`](https://elifesciences.org/content/5/e14472) data. It includes basic data processing and conversion using the [`mesoscope`](https://github.com/sofroniewn/mesoscope) package, as well as analysis of both low magnification and high magnification data using [`thunder`](https://github.com/thunder-project/thunder), [`thunder-extraction`](https://github.com/thunder-project/thunder-extraction), and [`thunder-registration`](https://github.com/thunder-project/thunder-registration).

## running remotely

You can use Binder to run a hosted version of this tutorial. Just click this badge.

[![Binder](https://img.shields.io/badge/launch-binder-red.svg?style=flat-square)](http://mybinder.org:/repo/freeman-lab/mesoscope-workshop)

## running locally

To run these notebooks locally, first make sure you have a recent version of Python 3 — we highly recommend using Anaconda.

Then clone this repository by typing

```
git clone https://github.com/freeman-lab/mesoscope-workshop
```

And inside the folder `mesoscope-workshop` type

```
pip install -r requirements.txt
```

Which will install all the dependencies.