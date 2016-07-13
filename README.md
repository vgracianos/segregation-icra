SEGREGATION-ICRA
================

Source code accompanying the paper *Segregation of Multiple Heterogeneous Units in a Robotic Swarm* presented at ICRA2014 ([DOI][http://dx.doi.org/10.1109/ICRA.2014.6906993]).

<center>
[![ICRA 2014 Video](https://img.youtube.com/vi/tN6yEOUU00I/hqdefault.jpg "ICRA 2014 Video")](https://www.youtube.com/watch?v=tN6yEOUU00I)
</center>

Abstract
--------

Several natural systems adopt self-sorting mechanisms based on
segregative behaviors. Among these, cell segregation is of particular
interest since it plays an important role in the formation of tissues,
organs, and living organisms. The Differential Adhesion Hypothesis
states that cells naturally segregate because of differences in
affinity, which lead similar cells to strongly adhere to each
other. By exploring this principle, we propose a controller that can
segregate a heterogeneous swarm of robots according to the
characteristics of each agent, such that similar robots form
homogeneous teams and dissimilar robots are segregated. We apply
LaSalle's Invariance Principle to show convergence and perform
simulated experiments in order to demonstrate the robustness and
effectiveness of the proposed controller. Results show that our
approach allows a swarm of multiple heterogeneous robots to segregate
in a coherent and smooth fashion, without any inter-agent collisions.

Source Files
------------

Name            | Description
----------------|----------------------------------------------
segregation2d.m |  MATLAB example for swarm segregation in 2D
segregation3d.m |  MATLAB example for swarm segregation in 3D
article/        |  LaTeX source files (use pdflatex to compile)




