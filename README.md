---
title: 'Knowledge graphs and wikidata subsetting'
title_short: 'Knowledge graphs and wikidata subsetting'
tags:
  - Wikidata
  - ShEx
  - RDF
  - Knowledge graphs
authors:
  - name: Jose Emilio Labra Gayo
    orcid: 0000-0001-8907-5348
    affiliation: 1
  - name: Ammar Ammar
    affiliation: 2
  - name: Dan Brickley
    affiliation: 3
  - name: Daniel Fernández Álvarez
    affiliation: 1
  - name: Alejandro González Hevia
    orcid: 0000−0003−1394−5073
    affiliation: 1
  - name: Alasdair Gray
    affiliation: 4
  - name: Eric Prud'hommeaux
    affiliation: 5
    orcid: 0000-0003-1775-9921
    affiliation: 1
  - name: Denise Slenter
    affiliation: 2
  - name: Harold Solbrig
    affiliation: 6
  - name: Seyed Amir Hosseini Beghaeiraveri
    affiliation: 4
  - name: Benno Fünkfstük
    affiliation: 8
  - name: Andra Waagmeester
    affiliation: 7
  - name: Egon Willighagen
    affiliation: 2
  - name: Liza
    affiliation: 3
affiliations:
  - name: WESO research group, University of Oviedo, Spain
    index: 1
  - name: Maastricht University
    index: 2
  - name: Google, London, UK
    index: 3
  - name: Heriot Watt University, UK
    index: 4
  - name: Janeiro Digital, W3C/MIT
    index: 5
  - name: Johns Hopkins University
    index: 6
  - name: Micelio/Gene Wiki
    index: 7
  - name: TU Dresden
    index: 8
date: 14 January 2021
bibliography: paper.bib
event: BH20EU
group: Wikidata subsetting
authors_short: Jose E. Labra \emph{et al.}
---

<!--

The paper.md, bibtex and figure file can be found in this repo:

  https://github.com/kg-subsetting/preprint-biohackrxiv

-->

# Introduction

- Short sentence about Knowledge graphs and wikidata. 
- Talk about entity schemas at Wikidata which are based on ShEx [@EricSemantics2014]

## Motivation

TODO

## Use cases

# Description of different approaches and pipeline

![Diagram presenting the different approaches \label{fig}](./schema.png)

## Describing the subsets

- Using Entity schemas created manually
- Generating entity schemas from instance data

## Wikidata subsetting language

- TODO: Describe the idea...
- Generates SPARQL Construct queries

# Extraction of subsets from wikidata

## Slurping 

## WDumper

# Creating the subset

- Transforming and enriching the RDF dump using schema.org
- WikidataIntegrator

# Discussion

TODO: Review...

- Talk about docker image
- Future work: Wikidata subsetting as a service?

# Conclusions


# References
