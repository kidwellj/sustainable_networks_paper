# Sustainable Networks

This repository contains the code and writing towards a (working draft of a) scholarly paper which presents a social network analysis of eco-groups in the UK using Twitter data from representative groups. The paper is written in R Markdown and for the most part, I'm using the conventions outlined by Kieran Healy [here](https://kieranhealy.org/blog/archives/2014/01/23/plain-text/) and is best viewed (I think) in [R Studio](https://www.rstudio.com) though it will be reasonably comprehensible to anyone using a Markdown editor. If I'm not working in RStudio, I'm probably in Sublime text, FYI.

Eventually, R code will be integrated into the text of this document. The idea is that this will serve as "[reproducible research](http://kbroman.org/steps2rr/)" by which anyone can download the contents of this repository, execute the R code which will gather data used from open and sustainable repositories, and then conduct the analysis I've done. I'd be extremely happy if someone found errors, or imagined a more efficient means of analysis and either reported them as an issue on this github repository or sent me an email.

The actual article is in `network_analysis.md`. 

The file `network_analysis.r` contains working code which will be eventually moved into a merged .RMd file.

Paths in this folder are used mostly for R processing. Towards this end folders have the following significance:

- `data` contains datasets used for analysis.
- `derived_data` contains files which represent modified forms of files in the above path.
- `figures` contains images and visualisations (graphic files) which are generated by R for the final form of the document.
- `cache` isn't included in github but is usually used for working files

Note: none of the contents of the above are included in the github repository unless they are unavailable from an external repository.