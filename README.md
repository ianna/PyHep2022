<div>
<img src="img/IRIS-HEP%20logo.png" width="200" align="right"/>
</div>

# Awkward RDataFrame Tutorial

This is the repository for the talk [Awkward RDataFrame Tutorial](https://indi.to/jh92b) presented at the [PyHEP 2022 Workshop](https://indico.cern.ch/event/1150631/) on September 15, 2022.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7081586.svg)](https://doi.org/10.5281/zenodo.7081586)

## Abstract

This Jupyter notebook tutorial will cover usage of Awkward Arrays within an RDataFrame.

In Awkward Array version 2, the ak.to_rdataframe function presents a view of an Awkward Array as an RDataFrame source. This view is generated on demand and the data is not copied. The column readers are generated based on the run-time type of the views. The readers are passed to a generated source derived from ROOT::RDF::RDataSource.

The ak.from_rdataframe function converts the selected columns as native Awkward Arrays.

The tutorial demonstrates examples of the column definition, applying user-defined filters written in C++, and plotting or extracting the columnar data as Awkward Arrays.

## Authors
<div>
<img src="img/Princeton%20logo.png" width="150" align="right"/>
</div>

- Ianna Osborne, Princeton University
- Jim Pivarski, Princeton University

## Acknowledgements
<div>
<img src="img/NSF%20logo.png" width="60" align="left"/>
</div>

Support for this work was provided by NSF cooperative agreement [OAC-1836650](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1836650) (IRIS-HEP)

