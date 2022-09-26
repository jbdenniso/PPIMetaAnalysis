# PPIMetaAnalysis
This is a repository with the data and code associated with "Reward-Dependent Corticostriatal Connectivity:
A Meta-analysis of Psychophysiological Interactions".

## PPI-ALE.ipynb
This is a jupyter notebook containing the code used to perform the cooridnate based meta analysis

## Sleuth files
This folder contains the sleuth files used in the CBMA the files are named
Seed_construct.txt

  Seeds may be:
  1. STR
  2. PFC
  3. both


  Constructs may be:
  1. Ant (anticipation), Cons (consumption), learn (Learning), Value (valuation)
  2. or Pre (anticipation + valuation), Post (Consumption + Learning)
  3. or Dec (Valuation + Learning) Nodec (anticipation + Consumption)
  
  - Sleuthfiles named STR_seed.txt and PFC_seed.txt contain the coordinates for the meta seeds.
  - Sleuthfiles named STR_targe.txt and PFC_target.txt contain the target coordinates of PPI studies across all constructs.


## The CBMA_info.xlsx is a spreadsheet containing raw data recorded from the publication search and recording.
There are 5 main sheets:
1.) Prisma diagram: Reflexts the number of studies that have been excluded
2.) List of Studies the full list of studies from pubmed resulting from our search.
3.) Included a list of studies that passed the inclusion criteria
4.) CBMA info: Raw information and coordinates from included studies.
5.) Region by construct a count of studies based on the construct and seed.


