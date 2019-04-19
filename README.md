## Visual Cognition and Graphical Communication: Exploring Semantic Structure in Communicative Sketches
### Kushin Mukherjee
### Senior Undergraduate Thesis

-------

All python notebooks use Python 2.7

### Folder Descriptions

#### features 
This folder contains CNN features for intact and lesioned sketches as `*.npy` files as well as metadata files to help index the features within python.

#### helpers
Contains analysis helpers as well as scripts for extracting VGG 19 features from `*.png` files.

#### results/csv

Contains the annotated sketch data after filtering for sketches that were annotated 3 times + `*.png` data for the annotated sketches.

### sketches

Contains `*.svg` and `*.png` files for all the chairs in our analysis dataset

### notebooks

Contains all our main analysis notebooks. There are 3 notebooks -
`semantic_parts_dynanmics_part_feature.ipynb` - contains analysis scripts for thesis section: _*2.3.1.	Quantifying semantic structure in sketches*_


`semantic_parts_lesion.ipynb` - generates intact and lesion sketches

`lesion_analysis.Rmd `- contains analysis scripts for thesis section: _*2.3.2.	Importance of visual features of semantic parts in sketch recognition*_


