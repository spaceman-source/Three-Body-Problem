# Three-Body-Problem

ABSTRACT

   The three-body problem examines the motion of three masses interacting through gravity. Unlike 
the two-body problem, which has closed-form solutions, the three-body problem has no general 
closed form solution. This is because the three-body problem is a chaotic system which makes it 
unpredictable, but it is possible to use numerical methods to get an estimate. I utilized widely 
known Newtonian mechanics to compute the forces and acceleration of the bodies and integrated 
using the leapfrog integration technique to ensure the simulation follows energy conservation. 
Exceptions have been found for the three-body problem these are called “special solutions” they 
have known analytical solutions. These solutions  constrain the initial conditions for the three-body 
system by implementing specific mass ratios,  positions, and velocities, causing unique periodic 
trajectories that can be numerically solved.


INTRODUCTION

  The three-body problem originates from the work of Isaac Newton in the 17th century. After successfully 
describing two-body motion, Newton attempted to extend his methods to systems of three mutually interacting 
bodies. He found that the problem becomes significantly more complex, with no general closed-form solution. 
Figure 1 illustrates this showing the force of the bodies depend on the net gravitational force, which is 
determined by the relative position of the other two bodies. Since the position of the bodies is always changing 
the forces continuously update meaning the equations are coupled.  Since the equations are coupled and the 
force is non-linear(Equation.2), renders it difficult to find a general analytical solution. This is where special 
solutions take place these restrict or constrain the initial conditions to where the three-body problem is solvable. 
The objective of this work is to simulate  several of the known special solutions to the three-body problem
