# Pattern-Based Electron Counting Algo for LDMX TS

This is the software developed for the thesis "Pattern-Based Electron Counting Algorithm for LDMX," which can be read here: LINK. **NOTE: The files refered to as ClusterViewerAnalyzer and LUTAnalyzer have been renamed within *ldmx-sw* to ClusterTripletMaker and PatternLUTMaker, respectively.**

This software builds upon (and parts of it are included within) the GitHub repo *ldmx-sw*, found at LINK. To get started with using *ldmx-sw*, please see the tutorial: https://ldmx-software.github.io/using/analysis/ldmx-sw.html. You will need denv (see tutorial sec. 1) and if developing, see using just under sec. 11 of the tutorial. This repo contains *new* code written by me, but changes were made to other files in *ldmx-sw*, most importantly in `TrigScint/src/TrigScint/TrigScintTrackProducer.cxx` and its respective header file. You will need *ldmx-sw* v.XXX to access these files. These changes were merged in PR XXX. 

Described below is the workflow I used. 

## To run simulations: 

I used the file `NewEventcreator.py` to generate simulation samples. This file is run using: 

```just fire NewEventcreator.py``` 

I generated files in sets of n_ev= 10000 with different p.run_numbers each time. To generate Figs. x through y in my report I had to run these jobs on LUNARC using bash scripts to automate this process. Hans Alin has these scripts (?) 

## Analysis to reproduce my thesis: 

code: just fire 
denv fire? no development? 

just fire runClusterstxt.py 

(ALSO: EXTRUTHFIG)

just fire runLUTana.py 

just fire runLUTtracking.py 

----------
Include files to make plots: 

To reproduce Fig. xxx...

