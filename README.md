# This repository tests RQS bitmasks in DR16Q.

There appeared to be an issue with how RQS bitmasks were set in DR16Q_v3.fits compared to spAll-v5_13_0.fits. This repo demonstrates a more rigorous test of this issue in DR16Q_v4.fits, which is the current quasar catalog file.

# Required input files:
To execute this code, you will need DR16Q_v4.fits and spAll-v5_13_0.fits.  These can be obtained from the following locations:

https://www.sdss.org/dr16/algorithms/qso_catalog/

https://data.sdss.org/sas/dr16/eboss/spectro/redux/v5_13_0/ (<-- Warning! This file is ~15GB.)


# The RQS bitmasks:
The RQS bitmasks are given in EBOSS_TARGET2, and listed here:

https://www.sdss.org/dr16/algorithms/bitmasks/#EBOSS_TARGET2

# Results
See the Jupyter notebook.
