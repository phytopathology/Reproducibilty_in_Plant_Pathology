# Plant Pathology Journal Article Reproducibility Survey Results and Recomendations
A. H. Sparks, E. M. Del Ponte, N. J. Grünwald, and Z. Foster  
`r Sys.Date()`  


1. Adam H. Sparks: Centre for Crop Health, University of Southern Queensland,
Toowoomba, Qld 4350, Australia
2. Emerson M. Del Ponte: Universidade Federal de Viçosa, Viçosa, MG, Brasil
3. Zachary S. L. Foster: Department of Botany and Plant Pathology, Oregon State
University, Corvallis, OR 97330, USA
4. Niklaus J. Grünwald: Horticultural Crops Research Laboratory, USDA
Agricultural Research Service, Corvallis, OR 97330, USA

# ABSTRACT

Abstracts are mandatory and limited to one 200 word paragraph.

# MAIN TEXT

Reproducibility and replicability in scientific research have once again been
highlighted recently [@Nature_Editorial_2016; @Baker2016a] as an issue.

Patil et al. [-@Patil066803] have provided several definitions to clarify the
concepts surrounding reproducibility and replicability. For the purposes of this
paper we follow the definitions as given by Patil et al. [-@Patil066803].

* Why reproducible research

## BEST METHODS FOR REPRODUCIBLE RESEARCH

* Provide definitions (provide definitions for terms used so it's clear)

* Data

  * 10 things to make your data reproducible

  * Data formatting (flat files; use Comma Chameleon, Table Tool, others?)

  * Data storage (don't edit raw data files; use file permissions to prevent
  changes to raw data files, use data bases where possible and appropriate;
  etc.)

* When publishing

  * Provide data

  * Provide code

* Using GitHub for code (and small data?)

* Using Figshare or Zenodo vs a lab website (DOIs, other reasons)

## WHAT IS THE STATE OF REPRODUCIBLE RESEARCH IN PLANT PATHOLOGY?

* Madden et al. [-@Madden2015] supply an *e-**X**tra*\* with reproducible
examples for readers.

* Duku et al. [-@Duku2016] provide models, data and code,
(http://adamhsparks.github.io/MICCORDEA/) necessary to
replicate the entire study modelling the effects of climate change on rice
bacterial blight and rice leaf blast in Tanzania.

* Sparks et al. [-@Sparks2011; -@Sparks2014] provide models, data and code, (http://adamhsparks.github.io/Global-Late-Blight-MetaModelling/)
necessary to replicate model development and the subsequent the study on the
effects of climate change on potato late blight.

* Del Ponte provides data and a reproducible report that explain in details all
steps of the analysis and the R codes for conducting a meta-analysis for
assessing heterogeneity in relationship between white mold incidence and soybean
yield and between incidence and soybean tied.

* Example from Grünwald lab: 
  - paper http://apsjournals.apsnet.org/doi/full/10.1094/PHYTO-12-14-0350-FI
  - github repo https://github.com/grunwaldlab/Sudden_Oak_Death_in_Oregon_Forests

* Other examples from plant pathology providing e-Xtras or supplemental material

## RANDOM SAMPLING OF ARTICLES FROM THE TOP 20 PLANT PATHOLOGY JOURNALS

The 21 plant pathology discipline journals were selected by the authors as
representations of discipline-based journals where others in the field of
phytopathology are likely to publish were used to create a database of journals
from which to randomly select articles for inspection. Two hundred articles were
randomly selected from 2012 to 2016 from a list of randomly selected pages
assigned to a randomised list of the 21 journals [@Sparks2017] where the page
number fell within an article for the given journal. In cases where an article
was not suitable, _e.g._, a review or otherwise not related to plant pathology,
the next article was selected until a suitable article was found. Notes
regarding the selection of articles can be found in the file, XXXX, available in
this paper's repository. The pages list was numbered from page one and went to
150. This was done since some journals restart their numbering with each issue
and also ensures that the journal is more likely to have a page number
corresponding to the randomly generated value. This also assumes that there is
no effect or bias on reproducibility based on the time of year that an article
was published, since most journals start with page number one at the beginning
of the year.

The list of journals was saved as a comma separated value (CSV) file and
imported into R [@R2017]. 

## DISCUSSION

## ACKOWLEDGEMENTS

### LITERATURE CITED