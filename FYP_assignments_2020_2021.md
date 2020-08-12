## Assignment 1: Setup Git and GitHub

	- To install git, create an account at GitHub, fork a copy of BMSSlib or BMSS2 to their GitHub account. 
	- To create a folder named ‘FYP_username_2020_21’ at their GitHub account and share the folder with us. 


## Assignment 2: Model Simulation and Curve-fitting

	- After going through the sample codes provided in the link below:
	- https://github.com/EngBioNUS/Resources/blob/master/Introduction%20to%20Curve-Fitting.ipynb

1. Use a different model.
	- Suppose we want to simplify the model into a one-step process i.e. protein synthesis is directly controlled by the inducer with no mRNA involved. Write your own model function and repeat the steps above using your model.
	- Suppose we want to model gene expression as a two-step process plus one maturation step i.e. protein synthesis is followed by a first order maturation step. Write your own model function and repeat the steps above using your model.

2. Use a different optimizer.
	- Suppose we want to use differential evolution for curve-fitting. Repeat the steps above using scipy's differential evolution optimizer.
	- Suppose we want to use dual annealing for curve-fitting. Repeat the steps above using scipy's dual annealing optimizer.

3. Test your understanding
	- Why do we use sum squared error instead of simply summing up the errors directly?
	- Suppose we use an optimizer that searches for the maximum value of an objective function. Do we need to change the objective function? If so, how should we change it?

4. Analyze the results
	- The true parameters used to generate the data are shown in the cell above. Does your simulations always converge to the true parameters? Why? What are the underlying factors? How can we ensure that we can determine the true parameters? Does it always matter if we cannot determine the true parameters? (500 words)
