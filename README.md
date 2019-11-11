<img src="img/pr2_logo_16_9.png" width="10%" style="display: block; margin: auto;" />

Protist Ribosomal Reference database (PR<sup>2</sup>)
=====================================================

[![Release](https://img.shields.io/badge/release-4.12.0-blue.svg)
![Date](https://img.shields.io/badge/date-08%20August%202019-lightgrey.svg)
![Github Downloads
(total)](https://img.shields.io/github/downloads/pr2database/pr2database/total.svg)](https://github.com/vaulot/pr2_database/releases)

[![Twitter
URL](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=PR2%20database&url=https://github.com/vaulot/pr2_database&hashtags=PR2database)

SSU rRNA gene database
----------------------

The Protist Ribosomal Reference database (PR<sup>2</sup>) provides a
unique access to eukaryotic small sub-unit (SSU) ribosomal RNA and DNA
sequences, with curated taxonomy. The database mainly consists of
nuclear-encoded protistan sequences. However, metazoans, land plants,
macrosporic fungi are also included because they are useful for the
analysis of high-troughput sequencing data sets. Introns and putative
chimeric sequences have been also carefully checked. Taxonomic
assignation of sequences consists of eight unique taxonomic fields.

Since the original web site
(<a href="http://ssu-rrna.org/pr2" class="uri">http://ssu-rrna.org/pr2</a>)
does not exist any more, we are proposing updated version of
PR<sup>2</sup> and provide the data in a variety of file formats to use
for annotating metabarcodes.

Current version
---------------

-   Current version : 4.12.0
-   Last update : 8 August 2019
-   DOI :
    <a href="https://doi.org/10.6084/m9.figshare.5913181" class="uri">https://doi.org/10.6084/m9.figshare.5913181</a>
-   [Link to latest
    release](https://github.com/pr2database/pr2database/releases)
-   Manual :
    <a href="https://github.com/pr2database/pr2database/wiki" class="uri">https://github.com/pr2database/pr2database/wiki</a>

Downloading the database
------------------------

-   [Flat files - latest
    release](https://github.com/pr2database/pr2database/releases)

-   R package using Devtools - See [examples of
    use](https://github.com/pr2database/pr2database/wiki/PR2-R-database-package)

``` r
install.packages(devtools)
devtools::install_github("pr2database/pr2database")
```

Basic statistics
----------------

-   [PR<sup>2</sup>
    statistics](https://vaulot.github.io/pr2/PR2_analysis.html)

Report issues
-------------

-   Please report any issue on
    [GitHub](https://github.com/vaulot/pr2_database/issues)

Core Team
---------

-   [Daniel VAULOT](mailto:vaulot@gmail.com), [Laure
    GUILLOU](mailto:lguillou@sb-roscoff.fr), CNRS-Sorbonne Université,
    Station Biologique, 29680 Roscoff FRANCE
-   [Javier del CAMPO](mailto:jdelcampo@rsmas.miami.edu), University of
    Miami, USA
-   [Frédéric MAHE](mailto:frederic.mahe@cirad.fr), CIRAD, Montpellier,
    FRANCE

Contributors
------------

-   [Margot Tragin](mailto:margo.tragin@gmail.com) - Roscoff -
    Chlorophyta
-   [Adriana Lopes dos Santos](mailto:adriana.lopes@ntu.edu.sg) -
    Nanyang University, Singapore - Chlorophyta
-   [Chetan Gaonkar](mailto:chetan.gaonkar@gmail.com) - Naples -
    *Chaetoceros*
-   [Ramon Massana](mailto:ramonm@icm.csic.es) - ICM, Barcelona -
    Stramenopiles
-   [Bente Edvardsen](mailto:bente.edvardsen@bio.uio.no) - U of Oslo -
    Haptophyta
-   [Johan Decelle](mailto:johan.decelle@univ-grenoble-alpes.fr) - CNRS
    Roscoff - Plastid sequences (PhytoRef database)
-   Solenn Mordret - SZN, Naples - Dinophyta
-   Charles Bachy and Wei Ting Chen - Roscoff - Ciliates
-   Vittorio Boscaro - UBC, Vancouver- and the EukRef ciliate team -
    Ciliates
-   [Javier del Campo](mailto:jdelcampo@rsmas.miami.edu) - U of Miami -
    Apicomplexa
-   Tristan Biard - Wimereux Station - Radiolaria

Please cite
-----------

-   Guillou, L., Bachar, D., Audic, S., Bass, D., Berney, C., Bittner,
    L., Boutte, C. et al. 2013. [The Protist Ribosomal Reference
    database (PR<sup>2</sup>): a catalog of unicellular eukaryote Small
    Sub-Unit rRNA sequences with curated
    taxonomy](http://nar.oxfordjournals.org/lookup/doi/10.1093/nar/gks1160).
    Nucleic Acids Res. 41:D597–604.

Related Databases
=================

18S rRNA primer database (NEW)
------------------------------

The [PR<sup>2</sup> primer
database](https://github.com/pr2database/pr2-primers) is a compilation
of primers found in the litterature with an *in silico* analysis against
the PR<sup>2</sup> database.

Eukref (18S annotation)
-----------------------

<img src="img/eukref_logo.png" width="15%" style="display: block; margin: auto;" />

PR<sup>2</sup> is incorporating annotations made by the
[EukRef](http://eukref.org/) project as deposited in their [GitHub
repository](https://github.com/eukref/curation).

PhytoRef (16S plastid)
----------------------

<img src="img/phytoref_logo.png" width="20%" style="display: block; margin: auto;" />

Plastid 16S rRNA sequences have been included into PR<sup>2</sup>
version 4.12.0. The original [PhytoRef](http://phytoref.sb-roscoff.fr/)
database is still active.

PFR2 - Foraminifera 18S ribosomal DNA databae
---------------------------------------------

The database offers access to planktonic Foraminifera 18S ribosomal DNA
sequence library with a curated taxonomy at the morphological and
molecular level. The compilation was facilitated through the efforts of
the SCOR/IGBP Working Group 138 “Modern planktonic foraminifera and
ocean changes”.

[PFR2](http://pfr2.sb-roscoff.fr/)
