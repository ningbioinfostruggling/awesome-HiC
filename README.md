# Awesome-HiC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome collections of HiC-seq analysing softwares

The eukaryotic genome have hierarchical three_dimensional conformation, where physical contacts between chromatin have been proved to govern the regulation of gene expression. High-resolution chromosome conformation capture sequencing (HiC-seq) has been one of the most important methods to investigate the 3D genome since its first publication in 2009\. Since then, numerous of softwares and packages have been developed to facilitate the analysis of HiC-seq data.

Here is a curated **awesome** list of HiC-seq data related softwares/packages/intro-papers that are recommended for HiC data analysis and research.

Your contributions are always welcome!

## Contents

- [Comprehensive pipelines](#Comprehensive-pipelines)
- [Toolkits](#Toolkits)
- [Mapping & Filtering](#Mapping-filtering)
- [Normalisation](#Normalisation)
- [Visualisation](#Visualisation)
- [Significant contacts identification](#Significant-contacts-identification)
- [Topologically-Associated Domains identification](#Topologically-associated-domains-identification)
- [Other awesome HiC softwares](#Other-awesome-softwares-related-to-HiC-seq)
- [HiC-seq introduction papers/tutorials](#HiC-seq-introduction-papers/tutorials)

--------------------------------------------------------------------------------

## Comprehensive pipelines

_Pipelines to process HiC-seq data from raw/trimmed data input to interactions/matrices output_

- [HiC-Pro](https://github.com/nservant/HiC-Pro) ![made-with-bash](https://img.shields.io/badge/Bash-1f425f.svg) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [Juicer](https://github.com/aidenlab/juicer) ![made-with-java](https://img.shields.io/badge/Java-yellow.svg)

## Toolkits

_Toolkits that containing multiple tools to analyse HiC-seq data_

- [diffHiC](http://www.bioconductor.org/packages/release/bioc/html/diffHic.html) ![made-with-r](https://img.shields.io/badge/R-blue.svg)
- [Homer](http://homer.ucsd.edu/homer/interactions/) ![made-with-perl](https://img.shields.io/badge/Perl-green.svg)
- [TADbit](https://github.com/3DGenomes/TADbit) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [HiTC](http://bioconductor.org/packages/devel/bioc/html/HiTC.html) ![made-with-r](https://img.shields.io/badge/R-blue.svg)

## Mapping & Filtering

_Softwares/packages to conduct alignments and filtering of HiC-seq data_

- [HiCUP](https://www.bioinformatics.babraham.ac.uk/projects/hicup/) ![made-with-perl](https://img.shields.io/badge/Perl-green.svg) ![made-with-r](https://img.shields.io/badge/R-blue.svg)
- Other mapping strategies can be found in pipelines & Toolkits.

## Normalisation

_Softwares/packages to conduct matrix normalisation of HiC-seq data_

- Explicit fashion

  - [HiCNorm](http://www.people.fas.harvard.edu/~junliu/HiCNorm/) ![made-with-r](https://img.shields.io/badge/R-blue.svg)

- Implicit fashion

  - [Iterative Correction and Eigenvector decomposition (ICE)](https://bitbucket.org/mirnylab/hiclib) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)

## Visualisation

_Softwares/packages to conduct visualisation of HiC-seq data_

- [JuiceBox](https://github.com/aidenlab/Juicebox) ![made-with-java](https://img.shields.io/badge/Java-yellow.svg)
- [HiCPlotter](https://github.com/kcakdemir/HiCPlotter) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [Sushi](https://bioconductor.org/packages/release/bioc/html/Sushi.html) ![made-with-r](https://img.shields.io/badge/R-blue.svg)
- [HiGlass](http://higlass.io/) ![made-with-web](https://img.shields.io/badge/Web-based-brown.svg)

## Significant contacts identification

_Algorithms to identify significant contacts_

- [FitHiC](https://github.com/ay-lab/fithic) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [CHiCAGO](http://regulatorygenomicsgroup.org/chicago) ![made-with-r](https://img.shields.io/badge/R-blue.svg)

## Topologically-Associated Domains identification

_Algorithms to identify Topologically-Associated Domains (TADs)_

- [rGMAP](https://github.com/ningbioinfostruggling/rGMAP) ![made-with-r](https://img.shields.io/badge/R-blue.svg)
- [ClusterTAD](https://github.com/BDM-Lab/ClusterTAD) ![made-with-java](https://img.shields.io/badge/Java-yellow.svg)
- [Armatus](https://github.com/kingsfordgroup/armatus) ![made-with-cpp](https://img.shields.io/badge/Cpp-black.svg)
- [HiTAD](https://github.com/XiaoTaoWang/TADLib) ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [TopDom](http://zhoulab.usc.edu/TopDom/) ![made-with-r](https://img.shields.io/badge/R-blue.svg)

## Other awesome softwares related to HiC-seq

_Other softwares/packages_

- [HiC-QC](https://github.com/ningbioinfostruggling/HiC-QC): QC for preliminary HiC libraries. ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [Boost-HiC](https://github.com/LeopoldC/Boost-HiC): HiC patterns detection from low resolution HiC data. ![made-with-python](https://img.shields.io/badge/Python-organge.svg)
- [HiCPlus](https://github.com/zhangyan32/HiCPlus): Resolution Enhancement of HiC interaction heatmap. ![made-with-python](https://img.shields.io/badge/Python-organge.svg)

## HiC-seq introduction papers/tutorials

_Introduction papers/tutorials of HiC-seq_

- [Lieberman-Aiden, E., Van Berkum, N.L., Williams, L., Imakaev, M., Ragoczy, T., Telling, A., Amit, I., Lajoie, B.R., Sabo, P.J., Dorschner, M.O. and Sandstrom, R., 2009\. **Comprehensive mapping of long-range interactions reveals folding principles of the human genome.** science, 326(5950), pp.289-293.](http://science.sciencemag.org/content/326/5950/289) : The first paper describing HiC-seq.

- [Grob, S. and Cavalli, G., 2018\. **Technical review: a Hitchhiker's guide to chromosome conformation capture. In Plant Chromatin Dynamics** (pp. 233-246). Humana Press, New York, NY.](https://link.springer.com/protocol/10.1007/978-1-4939-7318-7_14) : Awesome review of introducing all chromosome conformation capture assays.

- [Schmitt, A.D., Hu, M. and Ren, B., 2016\. **Genome-wide mapping and analysis of chromosome architecture.** Nature reviews Molecular cell biology, 17(12), p.743.](https://www.nature.com/articles/nrm.2016.104#ref85) : Awesome review of HiC-seq normalisation methods and some of the TADs calling approaches.

- [Rao, S.S., Huntley, M.H., Durand, N.C., Stamenova, E.K., Bochkov, I.D., Robinson, J.T., Sanborn, A.L., Machol, I., Omer, A.D., Lander, E.S. and Aiden, E.L., 2014\. **A 3D map of the human genome at kilobase resolution reveals principles of chromatin looping.** Cell, 159(7), pp.1665-1680.](https://www.sciencedirect.com/science/article/pii/S0092867414014974?via%3Dihub) : Highest resolution of HiC-seq data available, and includes an awesome video explaining the 3D genome.

## License

[![CC0](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).
