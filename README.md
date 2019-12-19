### Analytical Methods for Electrical Engineering - Fall 2019

#### Topics:
1. Python
2. Sets, Functions, Relations, and Cardinality
3. Sequences, Limits, and Calculus
4. Linear Algebra
5. Differential Equations
6. Fourier Series and Transforms
7. Graphs
8. Probability
9. Neural Networks

#### Final: Differential Equations for Neural Networks 
[hw/kevin/HW10.ipynb](https://github.com/kegedy/EE502P/blob/dev/hw/kevin/HW10.ipynb)

The computational neural networks we have been studying are quite far from what is happening in biology. A slightly more realistic model is to admit that each neuron ![i](https://latex.codecogs.com/gif.latex?i) in a network has a time varying firing rate ![x_i](https://latex.codecogs.com/gif.latex?x_i), for ![i](https://latex.codecogs.com/gif.latex?i) equal ![1](https://latex.codecogs.com/gif.latex?1) to ![n](https://latex.codecogs.com/gif.latex?n). We let ![equation](https://latex.codecogs.com/gif.latex?%24W%20%5Cin%20%5Cmathbb%7BR%7D%5E%7Bn%20%5Ctimes%20n%7D%24) be weight matrix, and ![equation](https://latex.codecogs.com/gif.latex?%24b%20%5Cin%20%5Cmathbb%7BR%7D%5En%24). The dynamics of such a neural network are

<p align="center">
<img align="center" src="https://latex.codecogs.com/gif.latex?%24%24%20%5Cdot%20x_i%20%3D%20g%20%5Cleft%20%28%20%5Csum_%7Bj%3D1%7D%5En%20w_%7Bi%2Cj%7D%20x_j%20&plus;%20b_i%20%5Cright%20%29%20%24%24">
</p>

where is the nonlinearity
<p align="center">
<img align="center" src="https://latex.codecogs.com/gif.latex?g(x)&space;=&space;\frac{1}{1&plus;e^{-x}}&space;-&space;\frac{1}{2}&space;." title="g(x) = \frac{1}{1+e^{-x}} - \frac{1}{2} ." />
</p>

  - Show properties of a ring oscillator in a neural network
  - Create a bistable network
  - Create a network with two oscillating subnetworks such that one prevents the other from oscillating
  - Show properties of a random network


Latex rendering by [codecogs](https://www.codecogs.com/latex/eqneditor.php)
