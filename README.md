# NJOY external data files

This repository contains all external data files used by NJOY. It currently contains data files for the following:
- the Atomic Mass Evaluation (AME) from 2020
- the RIPL-3 database

## AME2020

The Atomic Mass Evaluation 2020 files stored in this repository can be found [here](https://www.anl.gov/phy/atomic-mass-data-resources) at Argonne National lab. The Atomic Mass Evaluation files are also available [here](https://amdc.impcas.ac.cn/) and [here](https://www-nds.iaea.org/amdc/).

References:

F.G.Kondev, M.Wang, W.J.Huang, S.Naimi, G.Audi, "The NUBASE2020 evaluation of nuclear physics properties", Chinese Physics C45, 030001, March 2021

W.J.Huang, M.Wang, F.G.Kondev, G.Audi and S.Naimi, "The Ame2020 atomic mass evaluation (I)", Chinese Physics C45, 030002, March 2021.

M.Wang, W.J.Huang, F.G.Kondev, G.Audi and S.Naimi, "The Ame2020 atomic mass evaluation (II)", Chinese Physics C45, 030003, March 2021.

The Atomic Mass Evaluation 2020 is based upon work supported by the U.S. Department of Energy, Office of Science, Office of Nuclear Physics.

License: [Creative Commons (CC-BY-3.0)](https://creativecommons.org/licenses/by/3.0/)

## RIPL-3

The following data from RIPL-3 is available:
- Discrete Levels and Decay Data (version from February 23, 2023)

The RIPL-3 files stored in this repository can be found [here](https://www-nds.iaea.org/RIPL-3/).

Reference:

R. Capote, M. Herman, P. Oblozinsky, P.G. Young, S. Goriely, T. Belgya, A.V. Ignatyuk, A.J. Koning, S. Hilaire, V.A. Plujko, M. Avrigeanu, O. Bersillon, M.B. Chadwick, T. Fukahori, Zhigang Ge, Yinlu Han, S. Kailas, J. Kopecky, V.M. Maslov, G. Reffo, M. Sin, E.Sh. Soukhovitskii, P. Talou, Nuclear Data Sheets - Volume 110, Issue 12, December 2009, Pages 3107-3214

License: [Creative Commons (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/)

# Configuration

This repository provides a configuration file (`njoy.config`) to point to the above mentioned external
data files for use in NJOY. The environmental variable `NJOY_DATAPATH` should be set to the location of
this repository so that NJOY can locate the configuration file.
