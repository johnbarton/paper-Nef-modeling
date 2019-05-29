### Modeling and in vitro testing of the HIV-1 Nef fitness landscape
**Barton JP<sup>&ast;</sup>, Rajkoomar E<sup>&ast;</sup>, Mann JK, Murakowski DK, Toyoda M, Mahiti M, Mwimanzi P, Ueno T, Chakraborty AK<sup>+</sup>, Ndung’u T<sup>+</sup>**

<sup>&ast;</sup> Equal contributions  
<sup>+</sup> Correspondence to [ndungu@ukzn.ac.za](mailto:ndungu@ukzn.ac.za), [arupc@mit.edu](mailto:arupc@mit.edu)  

## Data

Data used in our analysis is contained in the `/raw` folder. Processed data is stored in the `/input` and `/output` folders.

## Ising and Potts models

Ising and Potts models were inferred from the sequence alignments `raw/nef-B-clipped.fasta` and `raw/nef-C-clipped.fasta` using [ACE](https://github.com/johnbarton/ACE). Correlations computed from the sequence alignments, which serve as input to ACE, and output from the ACE program are included in the `/couplings` folder. See the main [ACE repository](https://github.com/johnbarton/ACE) for more information on these files.

## Analysis

All analysis performed for the paper is contained in the Jupyter notebook `nef-analysis.ipynb`. Figures produced here are stored in the `/figures` folder.
