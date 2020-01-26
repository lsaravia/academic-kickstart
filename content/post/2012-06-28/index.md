---
title: "Come together"
date: 2012-06-28T07:51:00-07:00
comments: true
authors:
- admin
tags:
 - Old posts
 - spatially explicit models
 - multifractals
 - neutral models
 - hierarchical competition models
---

Aggregation of objects is widespread phenomena in several sciences and
of course in biology and ecology. Two cases I found and seem interesting
to me are: the aggregation  in niche space: [The clumping transition in
niche competition](http://iopscience.iop.org/1742-5468/2010/05/P05005/),
and the aggregation in neutral models: [Clustering in neutral
ecology](http://pre.aps.org/abstract/PRE/v68/i6/e061912).\

This seems to depend only on the discreteness and finiteness of the
objects and space. And in both cases the clumps have sizes distributed
as power laws.\
Furthermore when you have aggregation [is possible that you will find
multifractals](http://www.nature.com/nature/journal/v335/n6189/abs/335405a0.html),
so is very possible that multifractals are widespread on ecological and
biological phenomena.

All this introduction is because my article in Oikos is available as
early view:

[Multifractal growth in periphyton
communities](http://onlinelibrary.wiley.com/doi/10.1111/j.1600-0706.2011.20423.x/abstract)\


And I added some new kind of measures to the [multifractal estimation
package](https://github.com/lsaravia/mfsba) oriented to estimate
multifractals in spatial species distributions, they are not like the
ones published by [Borda-de-Agua in American Naturalist](http://www.ncbi.nlm.nih.gov/pubmed/18707410). 

They are simpler, I think: the first is the multifractal spectra of the most
abundant species, and the second is a little bit more complex, it
requires two steps:

1) Assign the number 1 to the most abundant specie, the number two to
the second most abundant and so on, so the result is a surface with
higher numbers assigned to the most rare species.

2) Estimate the multifractal spectrum.

I did these to characterize species distribution in a model that is a mix of neutral spatially
explicit and [Tillman's model](http://www.esajournals.org/doi/abs/10.2307/1939377) that I am
analysing here:


 - [Spatial patterns and diversity in multi-species models of succession](http://dx.doi.org/10.6084/m9.figshare.91381).

{{% alert note %}}

The spatially explicit model was published as [Biodiversity collapse and early warning indicators in a spatial phase transition between neutral and niche communities]({{< ref "/publication/saravia-2018/index.md" >}})

{{% /alert %}}
