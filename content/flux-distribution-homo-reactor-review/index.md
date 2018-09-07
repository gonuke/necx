---
layout: node
uuid: flux-distribution-homo-reactor-review
title: Review of Reactor Flux Distributions in Homogenous Reactors
prerequisites:
  - 2grp-neutron-diffusion-solns-bare-homogeneous-reactors
learning_objectives:
  - recall the characteristic axial shape for a cylindrical homogenous reactor
  - recall the characteristic axial shape for a infinite slab homogenous reactor
  - recall the characteristic axial shape for a spherical homogenous reactor
references:
  - el-wakil.bib
assessments: 
  - 
...


# Flux Distributions in Bare Homogenous Reactors (Review)

The neutron flux distribution in bare homogenous reactors is often described
analytically by neutron diffusion with two neutron energy groups.  For a bare
reactor, the solution to the fast (high energy) group flux and the thermal
(low energy) group flux have the same shape, but different magnitudes.

The mathematical shape of the solution depends on the geometric shape of the
reactor.  For bare reactors, a standard approximation of the vacuum boundary
condition is to set the solution to zero at an extrapolated distance.  Thus,
the dimensions of the mathematical system, \(\tilde{R}\), are slightly larger
than the dimensions of the physical system, \(R\).

Table X provides the standard shapes for some common geometries.


Table X

| Geometry                                                   |      Flux Distribution                                                    |
|------------------------------------------------------------|---------------------------------------------------------------------------|
| infinite slab of thickeness $$\tilde{a}$$                  |    $$\cos \left( \frac{\pi x}{\tilde{a}} \right)$$                        |
| sphere of radius $$\tilde{R}$$                             |  $$\frac{\tilde{R}}{\pi r} \sin \left( \frac{\pi r}{\tilde{R}} \right )$$ |
| cylinder of radius $$\tilde{R}$$ and height $$\tilde{H}$$  |axial: $$\cos \left( \frac{\pi z}{\tilde{H}} \right)$$, radial: $$J_v \left( \frac{2.405 r}{\tilde{R}} \right )$$                 |

This figure show the shape of the solution for an infinite slab or the axial
dimension of a cylindrical reactor.

![Thermal and fast flux distributions (arbitrary units) for a ](../img/cos_flux.svg)


