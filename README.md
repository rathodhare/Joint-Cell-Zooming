# Joint-Cell-Zooming
In  the  modern  world,  using  cellular  communication  has  become  a  necessity  and  with  growing  demand  for  networkconsumption, the number of base-stations providing the facility has also increased considerably.  With this huge number ofusers and base-stations providing the service, choosing an optimal allocation of all users to base stations has no longerremained a simple problem.  There are various research work done along similar problems already like one approach usedby Prof.  Prasanna Chaporkar in his paper on Joint Cell Zooming.Utilizing  this  opportunity,  we  decided  to  try  and  solve  this  problem  as  an  Research  and  Development  project  un-der Prof.  Prasanna Chaporkar.  We start with defining the problem statement, then we analyse the complexity of theproblem - the problem turns out to be NP-Hard.  In order to achieve globally optimum solution, we can not do muchbetter than brute-force if we want a deterministic algorithm to find the solution.  We had initially tried to solve it using agreedy approach, but we could easily come up with a small sized counter example where in the greedy approach producesa result that is a local optimum but not a global optimum.  The example is presented in the simulation section, and wealso show that our other approach settles at the global optimum.  Hence, motivated from approach used by Prof.  PrasannaChaporkar in his paper on Joint Cell Zooming, we also decided to formulate our problem as a Potential Game and solveusing a probabilistic approach, that is Spatial Adaptive Play (SAP). This approach adds a certain degree of randomnessto regular BRD algorithm so that it doesn’t get stuck in local optima.
