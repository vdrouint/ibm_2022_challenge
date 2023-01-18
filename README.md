# IBM Quantum: Open Science Prize 2022

This repository contains the Rutgers QC team's solution to the 2022 Open Science Prize. It consists of preparing a faithful ground state for the spin-1/2 Heisenberg model on the Kagome lattice through the Variational Quantum Eigensolver (VQE) method.

Below are some of the essential elements of the challenge:
- Solution may only be executed on the designated device (ibmq_guadalupe)
- Each submission must use the VQE algorithm to optimize and measure the ground state energy under the specified Hamiltonian and lattice as outlined in the included Jupyter Notebook.
- Only use libraries that can be installed using either pip install or conda install, and no purchased libraries.
- Document code with concise, clear language about the chosen methodology.
- The relative error of the measured ground state energy must be below 1% for consideration.

The submission will be judged on the following criteria:
- Performance as measured by the relative error of the measured ground state energy w.r.t. the exact value in comparison to other submissions (Max 25 points).
- Scalability of the solution to larger qubit devices and larger kagome lattices (Max 5 points)
- Creativity in developing a unique, innovative, and original solution (Max 5 points)
- Clarity of provided documentation and solution code (Max 5 points)

I.e. the goal is to get the closest to E=-18 (ground state energy), scale the algorithm to other heavy-hex architecture (therefore embedding more Kagome unit-cell) and innovate on the classical solver (perhaps in a fast-slow method). Code should be fully documented and annotated. 
