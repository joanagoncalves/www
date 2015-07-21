---
layout: page
permalink: /software/
title: Software
description: "Software developed by Joana P. Gonçalves"
image:
  feature: voronoi.jpg
  credit: Voronoi tesselation
  creditlink: http://bl.ocks.org/mbostock/4060366
---

## LateBiclustering

[**LateBiclustering**](https://dx.doi.org/doi:10.1109/TCBB.2014.2312007) is an efficient algorithm for time-lagged bicluster identification, recently published in IEEE/ACM Transactions on Computational Biology and Bioinformatics. The next release of the [**BiGGEsTS**](http://dx.doi.org/doi:10.1186/1756-0500-2-124) software will include **LateBiclustering**. In the meantime, please feel free to contact me if you are interested in applying LateBiclustering to your data. [`article`](https://dx.doi.org/doi:10.1109/TCBB.2014.2312007)

## BiGGEsTS

**BiGGEsTS** is a software for biclustering analysis of time series data. Although it has been originally introduced in the context of gene expression time series, most of the software's functionalities can be applied to time series in any domain of knowledge. BiGGEsTS includes data preprocessing techniques, state of the art temporal biclustering algorithms ([**CCC-Biclustering**](http://dx.doi.org/10.1109/TCBB.2008.34), [**e-CCC-Biclustering**](http://dx.doi.org/10.1186/1748-7188-4-8)), bicluster post-processing methods, and different kinds of visualisation. In its next release, BiGGEsTS will also integrate our latest [**LateBiclustering**](https://dx.doi.org/doi:10.1109/TCBB.2014.2312007) for efficient time-lagged biclustering. [`article`](http://dx.doi.org/doi:10.1186/1756-0500-2-124) [`software`](http://kdbio.inesc-id.pt/software/biggests)

**Biclustering** can be seen as simultaneous clustering on both dimensions of a data matrix (2D vector), or selection of submatrices, according to certain homogeneity criteria. For a reference, see the [survey by Madeira and Oliveira](http://dx.doi.org/10.1109/TCBB.2004.2). **Temporal biclustering** denotes a type of biclustering specifically tailored for the analysis of time series data. Temporal biclustering is aware and takes advantage of time properties to both deliver temporally-coherent results and enable a significant reduction of the problem's computational complexity (leading to the design of efficient algorithms).
{: .notice}

## TFRank

**TFRank** is a framework for ranking and highlighting key transcription factors putatively involved in the regulation of a set of target genes of interest. It uses a graph diffusion approach to propagate an initial signal on the targets through the network of regulatory interactions, which traverses the edges in the reverse direction (from targets to regulators) and accumulates a relevance score at every node. [`article`](http://dx.doi.org/doi:10.1093/bioinformatics/BTR546) [`software`](http://kdbio.inesc-id.pt/software/tfrank)

## Regulatory Snapshots

**Regulatory Snapshots** combines temporal biclustering on time course gene expression data and ranking of transcription factors to identify regulatory modules composed of genes exhibiting a similar expression profile in a given time frame, together with potential key regulators at each time point. [`article`](http://dx.doi.org/doi:10.1371/journal.pone.0035977) [`software`](http://kdbio.inesc-id.pt/software/regulatorysnapshots)

## Polar Mapper

**Polar Mapper** is a software tool originally proposed for integrated analysis of protein interaction networks and expression data. It does topology-based graph clustering and a polar map inspired visualisation with superposition of nodes' properties. [`article`](http://dx.doi.org/doi:10.1098/rsif.2008.0407) [`software`](http://kdbio.inesc-id.pt/software/polarmapper)