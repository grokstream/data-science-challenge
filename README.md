# data-science-challenge

Get NASA's solar flare data here:

Data:
https://hesperia.gsfc.nasa.gov/hessidata/dbase/hessi_flare_list.txt

Data columns explained (ignore the ones that are not listed):
Flare: an ID
Start time, peak, end: The start, peak energy, end of flare
Dur: Duration of the flare
Peak c/s: Maximum cycles per second of flare
Energy kEv: Energy emitted from flare 

1. Cleanse and extract the data in a useable format for machine learning. Ideally into a database. Please use Python
2. Perform analysis on the data to find "interestingness" or correlations among the columns (if any). 
3. Perform anomaly detection on the Dur (duration in seconds) column. It's up to you how you approach this. The timestamps for the data are also in random intervals, it's your choice how you approach this.

Caveat: Do not use Numenta's Nupic algorithms for anomaly detection (its what we use). Anything else is fine, Tensorflow, from scratch, etc. 

