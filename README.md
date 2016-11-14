# Project
Nate Stodick and Hemmerle's Final Project
#Proposal

##Introduction: 
We would like to model our magnetic particle trap with various geometries in a way that it would be possible to calculate the magnetic field at any point during the particle. If possible, we would also like to model this in 3D (although this is the far-reaching goal). As far as the physics goes, we need to use a magnetic susceptibility that is linear in the magnetic trap pieces. (as of right now, they are approximated as being infinite). The physics is fairly complicated (and truthfully, we have not gotten around to looking deeply at it) although, I’ve been assured that this linear magnetic susceptibility should be possible.

##Code Description:
We will use the iterative (relaxation) method to solve the system of partial differential equations in order to solve for the magnetic field in the trap. We will probably over-relax in order to try to get it to settle as quickly as possible (although we might try under and normal relaxation). We really want to use the linear susceptibility. If we could find a generic algorithm for simple shapes (like squares and specific triangles) that would also be nice.


##Analytic Solution: 
I’m not sure that there is an analytic solution to our problem; maybe if we approximate flat pull pieces with infinity magnetic susceptibility and vacuum of 0. But still not sure if it’s analytic


##Test Cases: 
We have a version our trap with the approximations stated earlier. Our code should match the magnetic field that that code produces. This would be our test case.
Alternatively, we could do very simple geometries and values of magnetic susceptibility.





