# project 1: Edge-Aware Filtering

Assigned: 2011/10/20  
Due: 2011/11/09 11:59pm  
url: http://www.csie.ntu.edu.tw/~cyy/courses/comphoto/11fall/assignments/proj1/

## Project description

In the class, we have introduced a bunch of edge-aware filtering: bilateral,
WLS, Local extrema, Diffusion map, Domain transform, Local Laplacian, L0
minimization and Guided filter. In this assignment, you have three options. For
the first option, you have to implement one of Local extrema or Diffusion map
(which do not have their source codes released). You are free to use any
language of your choice. For the second option, you can implement one of the
following filters, bilateral, WLS, Guided filter, Domain transform, local
Laplacian and L0 minimization (which have made their matlab codes publically
available) with a language other than matlab. In the third option, you are
asked to compare at least three of the following filters, bilateral, WLS,
Guided filter, Domain transform, local Laplacian and L0 minimization (which
have made their code publically available). Note that, since these options have
different levels of difficulty, option #1 has the highest baseline grade,
followed by option #2 and option #3 has the lowest. You are asked to use detail
manipulation as the example to illustrate your filter or to compare filters.
Other applications will be counted as bonus. 

## Project features

* Option #1 is chose for this assignment, plus the option #3's testing.
* Local Extrema filtering is implemented as matlab.
* The interpolation function in **Colorization Using Optimization** is used.
* For some reason, I might not test all filtering algorithms.
* There are around 8 testing images located in **input_images**.
* The resulting images are located in **result**.
* For each combination of one filter and one testing image, the resulting images are named as:
    * **image name**_**function name**_by_**filter name**
    * function name: smoothed(M), detail(D), enhanced(D\*2+I)
    * function name: plot_IMD: plotting of one line for its I, M, D.
    * filter name: wlsFilter, bilateralFilter, localExtrema, domainTransform, guidedFilter, l0Minimization, ...

## Results


## Reference

1. S. Paris and F. Durand, A Fast Approximation of the Bilateral Filter Using a Signal Processing Approach, IJCV 2009. ([matlab code](http://people.csail.mit.edu/jiawen/software/bilateralFilter.m))
2. Z. Farbman, R. Fattal, D. Lischinski, R. Szeliski, Edge-Preserving Decompositions for Multi-Scale Tone and Detail Manipulation, SIGGRAPH 2008. ([matlab code](http://www.cs.huji.ac.il/~danix/epd/wlsFilter.m))
3. K. Subr, C. Soler, F. Durand, Edge-Preserving Multiscale Image Decomposition Based on Local Extrema, SIGGRAPH Asia 2009.
4. Z. Farbman, R. Fattal, D. Lischinski, Diffusion Maps for Edge-Aware Image Editing, SIGGRAPH Asia 2010.
5. E. Gastal, M. Oliveira, Domain Transform for Edge-Aware Image and Video Processing, SIGGRAPH 2011. ([matlab code](http://inf.ufrgs.br/~eslgastal/DomainTransform/DomainTransformFilters-Source-v1.0.zip))
6. S. Paris, S. Hasinoff, J. Kautz, Local Laplacian Filters: Edge-Aware Image Processing with a Laplacian Pyramid, SIGGRAPH 2011. ([matlab code](http://people.csail.mit.edu/sparis/publi/2011/siggraph/matlab_source_code.zip))
7. L. Xu, C. Lu, Y. Xu, J. Jia, Image smoothing via L0 Gradient Minimization, SIGGRAPH Asia 2011. ([matlab code](http://www.cse.cuhk.edu.hk/~leojia/projects/L0smoothing/L0smoothing.zip))
8. K. He, J. Sun, X. Tang, Guided Image Filtering, ECCV 2010. ([matlab code](http://personal.ie.cuhk.edu.hk/~hkm007/eccv10/guided-filter-code-v1.rar))
