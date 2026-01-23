# ReadMe File for “When the Dust Settles: Israel Boycott Appeals on Bluesky After the Ceasefire”  
Authors: XYZ & XYZ

## Analysis Files  
The final folder contains the following files.

01 and 02 are Python scripts that connect to the Bluesky API. File 01 conducts   
keyword searches for the boycott target and victim/institutional context. File   
02 collects posts for keywords regarding the boycott action.

- 01_bluesky_tarvic_collection.py  
  Estimated runtime: approx. 4.5 hours  
  
- 02_bluesky_action_collection.py  
  Estimated runtime: approx. 15 minutes 

The pre-processed, classified dataset is produced in files 03 and 04. 

- 03_data_prep.R  

- 04_classifier.py

- 05_applying_classifier.py

To only reproduce data analysis and visualistion (without pre-processing and  
classification), run file 06.

- 06_Israel Boycott Appeals on Bluesky.qmd


## Datasets

- The raw data collected from the API is stored under "/data/rawdata".

- The final pre-processed, classified dataset used for analysis is called  
"bluesky_classified" and is stored under "/data".


## Additional Files

- apa.csl
- references_israelboycott.bib
- preamble.tex
- README.md
- bluesky.Rproj
- requirements.txt

## Notes
- R Version: 4.5.2, R Studio Version: 2026.01.0+392 
- Python Version: 3.13.7
  
### Required R packages and Python libraries:
(for Python, see requirements.txt)

ggpubr
grid
kableExtra
lubridate
marginaleffects
MASS
readxl
stringr
texreg
tidycomm
tidyverse
writexl
vtable