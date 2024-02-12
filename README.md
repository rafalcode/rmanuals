#rmanuals (well, nearly)

This is not my stuff!, it's a centralised point to get at the R reference manuals!

Why the "nearly"? ... because there's other stuff here: such as stata manuals, and, oh,
the online stats book from Rice Uni. About which:

note that the datasets are not in that, you have to go to the website https://onlinestatbook.com to get those).
However, they ARE listed. What good is that you might say?
Hmmm .. take a look at the name of dataset no .3 and you'll under sand why :-)
("Flatulence")

# seqgendiff
This is by D Gerard, the American University guy, working solo, who calls every variable a surrogate.
seqgendiff simulates rnaseq data using an existing dataset.
I've often gone looking for it.

# pgfmanual
Not actually R, but Tex did influence Rmd files so it's OK. PGF is closely related to tikz
and hold promised for fixed image placement.

# EdgeR vignette
This is a one pager, it devolves responsibility to the userguide. In fact I will reporduce the test here as it is not worthwhile to download it.
edgeR Package Introduction
Yunshun Chen, Davis McCarthy, Aaron Lun,
Xiaobei Zhou, Mark Robinson, Gordon K. Smyth
10 October 2012
Revised 8 October 2014
edgeR is a package for the dierential expression analysis of digital gene expression
data, that is, of count data arising from DNA sequencing technologies. It is especially
designed for dierential expression analyses of RNA-Seq or SAGE data, or dierential
marking analyses of ChIP-Seq data.
edgeR implements novel statistical methods based on the negative binomial distribution as a model for count variability, including empirical Bayes methods, exact tests,
and generalized linear models. The package is especially suitable for analysing designed
experiments with multiple experimental factors but possibly small numbers of replicates.
It has unique abilities to model transcript specic variation even in small samples, a capability essential for prioritizing genes or transcripts that have consistent eects across
replicates.
The full edgeR User's Guide is available as part of the online documentation. To
reach the User's Guide, install the edgeR package and load it into an R session by
library(edgeR). In R for Windows, the User's Guide will then be available from the
drop-down menu called Vignettes. In other operating systems, type
> library(edgeR)
> edgeRUsersGuide()
at the R prompt to open the User's Guide in a pdf viewer.

# ComplexHeatmap, poor "exampling"
Yes, ComplexHeatmap reference often just says "no example" ... considerably more times thatn any other package I know.

# Polyester 
A simulation packages, but in fact it goes in what I would call a reverse direction. It takes counts and simulates the reads from them.

# network D3 getting old
verfied late 2023 only oct 2022 manual available :-(

# MEGENA
same as ofr network 3D
verfied late 2023 only oct 2022 manual available :-(
vignette ... very elementary .. still wants you to name the moduels to plot.
