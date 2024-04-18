# FinAI2023
The code for [**_"An algorithm for computing Schubert Varieties of Best Fit with applications"_**](https://www.frontiersin.org/articles/10.3389/frai.2023.1274830/full) published in [Frontiers in Artificial Intelligence](https://www.frontiersin.org/journals/artificial-intelligence) in 2023
=======
<p align="center">
  <img src="https://raw.githubusercontent.com/kkarimov/FinAI2023/main/abstract_nodes_slides.png" alt="" style="height: 300px; width: 44%; margin: 0px; display: inline-block; vertical-align: top;">
  <img src="https://raw.githubusercontent.com/kkarimov/FinAI2023/main/fig10.jpg" alt="" style="height: 300px; width: 54%; margin: 0px; display: inline-block; vertical-align: top;">
</p>


## License
This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/) or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

Please cite as:

```bibtex
@ARTICLE{10.3389/frai.2023.1274830,
  
AUTHOR={Karimov, Karim and Kirby, Michael and Peterson, Chris},   
	 
TITLE={An algorithm for computing Schubert varieties of best fit with applications},      
	
JOURNAL={Frontiers in Artificial Intelligence},      
	
VOLUME={6},           
	
YEAR={2023},      
	  
URL={https://www.frontiersin.org/articles/10.3389/frai.2023.1274830},       
	
DOI={10.3389/frai.2023.1274830},      
	
ISSN={2624-8212},   
   
ABSTRACT={We propose the geometric framework of the Schubert variety as a tool for representing a collection of subspaces of a fixed vector space. Specifically, given a collection of l-dimensional subspaces V<sub>1</sub>, …, V<sub>r</sub> of ℝ<sup>n</sup>, represented as the column spaces of matrices X<sub>1</sub>, …, X<sub>r</sub>, we seek to determine a representative matrix K∈ℝ<sup>n×k</sup> such that each subspace V<sub>i</sub> intersects (or comes close to intersecting) the span of the columns of K in at least c dimensions. We formulate a non-convex optimization problem to determine such a K along with associated sets of vectors {a<sub>i</sub>} and {b<sub>i</sub>} used to express linear combinations of the columns of the X<sub>i</sub> that are close to linear combinations of the columns of K. Further, we present a mechanism for integrating this representation into an artificial neural network architecture as a computational unit (which we refer to as an abstract node). The representative matrix K can be learned in situ, or sequentially, as part of a learning problem. Additionally, the matrix K can be employed as a change of coordinates in the learning problem. The set of all l-dimensional subspaces of ℝ<sup>n</sup> that intersects the span of the columns of K in at least c dimensions is an example of a Schubert subvariety of the Grassmannian GR(l, n). When it is not possible to find a Schubert variety passing through a collection of points on GR(l, n), the goal of the non-convex optimization problem is to find the Schubert variety of best fit, i.e., the Schubert variety that comes as close as possible to the points. This may be viewed as an analog of finding a subspace of best fit to data in a vector space. The approach we take is well-suited to the modeling of collections of sets of data either as a stand-alone Schubert variety of best fit (SVBF), or in the processing workflow of a deep neural network. We present applications to some classification problems on sets of data to illustrate the behavior of the method.}
}
```

<p>&nbsp;</p>

