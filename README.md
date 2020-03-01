# data-active-exploration-hmdp

This repository is for providing data used in the paper about active exploration submitted to IROS 2020.


(under construction)

* ./modality-data/training/
  * vdata.csv ... Visual information for each object (m^v).
  * asdata.csv ... Auditory information obtained by shaking each object (m^as).
  * ahdata.csv ... Auditory information obtained by hitting each object (m^ah).
  * hdata.csv ... Haptic information for each object (m^h).

  The n-th row shows a BoF representation for the n-th object.

* ./modality-data/test/
  * object#{j}\_#{m}.csv
  
  The index #{j} represents the index of an object.
  the index #{m} represents the index of a modality.
  Each text file contains BoF obtained by each action.
