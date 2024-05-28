---
layout: default
title: Documents
---

<div id ="documents">

<h3> Documents shared-<h3>

<p><h4>[2018 ACM SIGSIM PADS]</b> Mohammad Abu Vickie, Jason Liu, Gopinath Chennupati, Nandakishore Santhi and  Stephan Eidenbenz, Parallel Application Performance Prediction Using Analysis Based Models, 2018 Principles of Advanced Discrete Simulation (PADS), Rome,Italy, 23 May 2018.</h4>

Parallel application performance models provide valuable insight 
about the performance in real systems. Capable tools providing fast, accurate,  
and comprehensive prediction and evaluation of high-performance computing (HPC) 
applications and system architectures have important value.  This paper presents 
<i>PyPassT</i>, an analysis based modeling framework built on static program analysis 
and integrated simulation of target HPC architectures.  More specifically, 
the framework analyzes application source code written in C with OpenACC 
directives and transforms it into an application model describing its computation 
and communication behavior (including CPU and GPU workloads, memory accesses, 
and message-passing transactions).  The application model is then executed 
on a simulated HPC architecture for performance analysis.  Preliminary experiments 
demonstrate that the proposed framework can represent the runtime behavior of 
benchmark applications with good accuracy.
</p>


<p><h4> [2017 Wintersim] Mohammad Abu Vickie and Jason Liu, Simulation of HPC Job Scheduling and Large-Scale Parallel Workloads, 2017 Winter Simulation Conference (WSC 2017), Las Vegas, NV, December 2017. </h4>
The paper presents a simulator designed specifically for evaluating
job scheduling algorithms on large-scale HPC systems.  The simulator
was developed based on the Performance Prediction Toolkit (PPT), which
is a parallel discrete-event simulator written in Python for rapid
assessment and performance prediction of large-scale scientific
applications on supercomputers.  The proposed job scheduler simulator
incorporates PPTs application models, and when coupled with the
sufficiently detailed architecture models, can represent more
realistic job runtime behaviors.  Consequently, the simulator can
evaluate different job scheduling and task mapping algorithms on the
specific target HPC platforms more accurately.
</p>


</div>

