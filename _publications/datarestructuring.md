---
title: "Live Restructuring of Data Architecture"
collection: publications
permalink: /publication/datarestructuring
excerpt: 'This paper is about a proposal to restructure the data architecture of a portion of a large-scale climate simulation program. ACME (Accelerated Climate Model for Energy), now called Energy Exascale Earth System Model (E3SM) [Open Source Project Now Available](https://github.com/waltonmacey/E3SM).
date: 2016-05-16
venue: 'SE4Science16'
paperurl: 'https://se4science.org/'
citation: 'Macey, Walton. (2016). &quot;Live Restructuring of Data Architecture.&quot; <i>Journal 1</i>. '
---


[Download paper here](http://waltonmacey.github.io/files/LRDA.pdf)

In large-scale Earth System simulation codes, such as the Accelerated Climate Model for Energy (ACME), complex user derived data types (containing large number of variables) are designed to represent the interactions of atmosphere, ocean, land, ice, and biosphere to project global climate under a wide variety of conditions.

The following is our proposed approach to restructure the data architecture of a land component within the ACME project while the project is undergoing active development. The data architect for the land subsystem defines the new datatype requirements that would greatly simplify the implementation of terrestrial land submodels by converting more than 50 to just eight primary data-types. Since the code is developed with the community governance, we have to ensure that the restructuring does not interface the other development which, with dozens of changes occurring every day, make it impossible to work on a shared development branch.

The active development also occurs on almost five hundred branches, making it extremely difficult to assess potential interactions.
To address these challenges we have designed and started an iterative procedure for implementing the data restructuring and estimating both the effort it takes to restructure and the effort would save once the restructuring is implemented.

[Download paper here](http://waltonmacey.github.io/files/LRDA.pdf)

Macey, Walton. (2016). "Live Restructuring of Data Architecture" <i>SE4Science16</i>.
