# Brownian-motion
Simulating Browninan motion of a particle in a 2D plane that obeys the Langevin equation


Refer to the problem.pdf question 3 for full question.

The  particle follows the Langevin equation mentioned in the above pdf. The randomness is modelled as Gaussian white noise. We use numpy.random.normal function to generate it.
Check the jupyter notebook for the code.

D is the diffusion constant.
In the following images, notice how the range of motion of the particle increases as D increases from 1 to 10.

## Brownian motion with D=1
![D.png](D.png)

## Brownian motion with D=2
![D10.png](D10.png)
