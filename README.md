
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Repository for the paper “A new Framework for Quantifying Grave Wealth”

This repository contains the data and code for our paper:

> Nørtoft, Mikkel, (2022). *A new Framework for Quantifying Grave
> Wealth*. Name of journal/book <https://doi.org/xxx/xxx>

The paper quantifies grave wealth from eight different parameters, and
uses these to identify potential wealth classes and calculate Gini
indices using Moravian Corded Ware Culture (CWC) graves as a case study.
One of the eight parameters is (estimated) manufacturing time of grave
goods. The extensive Supplementary Information (SI) in this repository
goes into more detail about how manufacturing time is calculated based
on primarily experimental reference data, and then applied to
archaeological data from different material-specific parameters. The SI
(open SI.html in a separate window or tab) also elaborates on other
theoretical, methodological, and contextual aspects that could not fit
in the main paper. Apart from this, all R-scripts, reference data and
archaeological data (grave and grave good data from Moravian CWC, and
geodata for raw material sources from around Europe) used in the main
paper and the SI can be found in this repository.

### How to cite

Please cite this compendium as:

> Authors, (2022). *Repository for A new Framework for Quantifying Grave
> Wealth*. Accessed 15 aug 2022.

## Contents

The **analysis** directory contains:

-   [:file_folder: paper](/analysis/paper): R Markdown source document
    for manuscript. Includes code (or code references) to reproduce the
    figures and tables generated in the paper. See CAA journal for the
    main paper.
-   [:file_folder: data](/analysis/data): Data used in the analysis
    (both experimental reference data and archaeological data).
-   [:file_folder: scripts](/analysis/scripts): Scripts used in the
    analysis.
-   [:file_folder: figures](/analysis/figures): illustrations for the
    main paper
-   [:file_folder: supplementary-information](/analysis/paper/SI.Rmd):
    RMarkdown file for the Supplementary information (SI) with specifics
    on how manufacturing time and other value parameters in the main
    paper were calculated as well as extended description of
    theoretical, methodological, and contextual aspects that did not fit
    in the main paper. See prehistoricmap.com/quantwealth/SI.html for a
    rendered version or the same file at Zenodo
    -   [:file_folder: figures_SI](/analysis/figures_SI): illustrations
        for the Supplementary Information.

## How to run in your browser or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

The simplest way to work with this repository is to clone or download
it, and then: - open the `.Rproj` file in RStudio - run
`devtools::install()` to ensure you have the packages this analysis
depends on (also listed in the [DESCRIPTION](/DESCRIPTION) file). -
finally, open `analysis/paper/paper_word.Rmd` and knit to produce the
paper (some things were manually edited in official version of the paper
and may not appear in the re-knitted output), or run
`rmarkdown::render("analysis/paper/SI.Rmd")` in the R console to produce
the `SI.html` (takes some time to produce)

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
