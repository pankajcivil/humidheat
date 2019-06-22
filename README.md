# humidheat

First, obtain necessary data and edit masterscript to point to the proper directories.
    Download all scripts (both Main and Supporting) as well as the contents of the Data folder.
    From the ECMWF website, download 6-hourly 1000-mb ERA-Interim data for specific humidity (q), temperature (T), u-wind, and v-wind for 1979-2017.
    Additionally, use ecmwfdownloadscript.sh.py to download 2-m ERA-Interim T and Td data for 1979-2017.
    Then, use erainterimcalc2mtw to compute 2-m Tw for Southwest Asia.
Run masterscript with reloaddata=1 but all other loops=0.
Finally, run makefinalfigures to create any figures that are desired.

Contact Colin Raymond (csr859@gmail.com) with any questions.
