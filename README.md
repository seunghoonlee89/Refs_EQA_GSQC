# Overview
This repository collects some representative papers in relation to the article, "Is there evidence of exponential quantum advantage in quantum chemistry" by Seunghoon Lee et al. We created this list in response to a reviewer's comment that they were not aware of any claims of exponential quantum advantage (EQA) in quantum chemistry in the literature. The purpose of the list is not to criticize the papers or authors below in any way, but rather simply to provide a few examples that
show where and in what sense these statements exist in the literature. 

Note that the set below is only representative; many more such papers exist with alternative authors. Also some of the papers below are very highly cited in journals with broad audiences, others are less so, or may be in more specialized journals; our intent is to simply sample the literature out there.

While some papers contain quite direct statements about EQA for ground-state chemistry, others have more indirect statements or assumptions, which
might reasonably be interpreted by a reader to mean that EQA is implied. We discuss this in more detail with each reference. 

## Papers that state that ground-state computation is exponentially spedup on quantum computers

In these papers, there is generally some statement that obtaining the exact ground-state classically is exponentially expensive AND
a statement that quantum computation for the same task is exponentially faster. 

> ### Orthogonal State Reduction Variational Eigensolver for the Excited-State Calculations on Quantum Computers
> Q. X. Xie, S. Liu, Y. Zhao
> 
> [![DOI:10.1021/acs.jctc.2c00159](https://img.shields.io/badge/DOI-10.1021/acs.jctc.2c00159-blue.svg)](https://doi.org/10.1021/acs.jctc.2c00159)
> 
>> 
>> Some progress has been achieved in calculating the ground-state energies of molecules. The quantum phase estimation (QPE) algorithm has been shown to bring about exponential speedup over the currently best classical algorithms for determining the ground states of a given Hamiltonian.
>> 

> ### Generalized Unitary Coupled Cluster Wave functions for Quantum Computation
> J. Lee, W. J. Huggins, M. Head-Gordon, K. B. Whaley 
> 
> [![DOI:10.1021/acs.jctc.8b01004](https://img.shields.io/badge/DOI-10.1021/acs.jctc.8b01004-blue.svg)](https://doi.org/10.1021/acs.jctc.8b01004)
> 
>> 
>> It was shown early on that quantum phase estimation (QPE) provides an exponential speed-up over the best “currently” known classical algorithms for determining the ground state of the molecular Hamiltonian.
>> 

> ### Quantum chemistry simulation on quantum computers: theories and experiments
> D. Lu, B. Xu, N. Xu, Z. Li, H. Chen, X. Peng, R. Xu, J. Du
>
> [![DOI:10.1039/C2CP23700H](https://img.shields.io/badge/DOI-10.1039/C2CP23700H-blue.svg)](https://doi.org/10.1039/C2CP23700H)
>
>>
>> This is the same situation as in quantum chemistry, where given a time-independent Hamiltonian of a molecule, the first task is to calculate the ground state energy, i.e., the lowest eigenvalue of the Hamiltonian. In classical computers, it is a non-deterministic polynomial (NP) problem. All known classical algorithms for it require exponential time. On the other hand, quantum algorithm or quantum simulation is theoretically proved to be able to solve this problem efficiently, in polynomial time.
>>

> ### Progress toward larger molecular simulation on a quantum computer: Simulating a system with up to 28 qubits accelerated by point-group symmetry
> C. Cao, J. Hu, W. Zhang, X. Xu, D. Chen, F. Yu, J. Li, H. S. Hu, D. Lv, M. H. Yung
> 
> [![DOI:10.1103/PhysRevA.105.062452](https://img.shields.io/badge/DOI-10.1103/PhysRevA.105.062452-blue.svg)](https://doi.org/10.1103/PhysRevA.105.062452)
> 
>> 
>> The exact evaluation of the molecular ground state in quantum chemistry requires an exponentially increasing computational cost. Quantum computation is a promising way to overcome the exponential problem using polynomial-time quantum algorithms.


## Papers that state that electronic structure and/or full configuration interaction/exact diagonalization/computation of exact energies is exponentially spedup on quantum computers

These papers have the characteristics that (i) the main application discussed is ground-state electronic structure, and (ii) there are statements that quantum computers (may) exponentially speedup electronic structure/computation of exact energies/full configuration interaction/many-body simulations, without explicitly referencing exponential speedup for ground state electronic structure/exact ground-state energies/ground-state full configuration interaction/ground-state many-body simulations. For example, a prototype of such a statement might be "exact computation of the ground-state energy is exponentially hard classically; quantum phase estimation allows 
exact energies to be obtained in polynomial time". Because of the juxtaposition of these comments, and because of the emphasis of the papers on (i), one might assume EQA for ground-states is implied. 

> ### Elucidating reaction mechanisms on quantum computers
> M. Reiher, N. Wiebe, K. Svore, D. Wecker, M. Troyer
> 
> [![DOI:10.1073/pnas.1619152114](https://img.shields.io/badge/DOI-10.1073/pnas.1619152114-blue.svg)](https://doi.org/10.1073/pnas.1619152114)
> 
>> 
>> The promise of exponential speedups for the electronic structure problem has led many to suspect that quantum computers will one day revolutionize chemistry and materials science.
>> 

> ### Toward Density Functional Theory on Quantum Computers?
> B. Senjean, S. Yalouz, M. Saubanère
> 
> [![DOI:10.48550/arXiv.2204.01443](https://img.shields.io/badge/DOI-10.48550/arXiv.2204.01443-blue.svg)](https://doi.org/10.48550/arXiv.2204.01443)
> 
>> 
>> One of the nearest-term application of quantum computers is quantum chemistry, where the focus is on wavefunction theory (WFT) that targets a numerically exact solution of the electronic structure problem. While quantum phase estimation (QPE) algorithms are in principle capable of solving the problem in its entirety ... However, despite the exponential speed-up announced by quantum computers, it remains ... The full configuration interaction (FCI) method – equivalent to exact diagonalization – scales exponentially with respect to the system size, and an exponential speed-up is given by the KSDFT formalism or by employing quantum computers (QFCI).
>> 

> ### Towards quantum chemistry on a quantum computer
> B. P. Lanyon, J. D. Whitfield, G. G. Gillett, M. E. Goggin, M. P. Almeida, I. Kassal, J. D. Biamonte, M. Mohseni, B. J. Powell, M. Barbieri, A. Aspuru-Guzik, A. G. White 
> 
> [![DOI:10.1038/nchem.483](https://img.shields.io/badge/DOI-10.1038/nchem.483-blue.svg)](https://doi.org/10.1038/nchem.483)
> 
>> 
>> Exact first-principles calculations of molecular properties are currently intractable because their computational cost grows exponentially with both the number of atoms and basis set size. A solution is to move to a radically different model of computing by building a quantum computer, which is a device that uses quantum systems 
themselves to store and process data ...
It has been proposed that a quantum computer can simulate many-body physical quantum systems (such as molecules) and calculate their energies to a fixed accuracy with a number of quantum computational resources that increases only polynomially with the number of particles.
>> 

> ### Multi-qubit entanglement and algorithms on a neutral-atom quantum computer
> T. M. Graham, Y. Song, J. Scott, C. Poole, L. Phuttitarn, K. Jooya, P. Eichler, X. Jiang, A. Marra, B. Grinkemeyer, M. Kwon, M. Ebert, J. Cherek, M. T. Lichtman, M. Gillette, J. Gilbert, D. Bowman, T. Ballance, C. Campbel, E. D. Dahl, O. Crawford, N. S. Blunt, B. Rogers, T. Noel, M. Saffman 
> 
> [![DOI:10.1038/s41586-022-04603-6](https://img.shields.io/badge/DOI-10.1038/s41586--022--04603--6-blue.svg)](https://doi.org/10.1038/s41586-022-04603-6)
> 
>> 
>> The time required for a complete classical calculation of molecular energies scales exponentially with the number of electronic orbitals. However, quantum phase estimation allows polynomial time energy estimates.
>> 

> ### Dynamical mean field theory algorithm and experiment on quantum computers
> I. Rungger, N. Fitzpatrick, H. Chen, C. H. Alderete, H. Apel, A. Cowtan, A. Patterson, D. M. Ramo, Y. Zhu, N. H. Nguyen, E. Grant, S. Chretien, L. Wossnig, N. M. Linke, R. Duncan
> 
> [![DOI:10.48550/arXiv.1910.04735](https://img.shields.io/badge/DOI-10.48550/arXiv.1910.04735-blue.svg)](https://doi.org/10.48550/arXiv.1910.04735)
> 
>> 
>> The computationally challenging part arises from solving the effective problem of an interacting impurity coupled to a bath, which scales exponentially with system size on conventional computers. An exponential speedup is expected on quantum computers.
>> 

> ### An efficient adaptive variational quantum solver of the Schrödinger equation based on reduced density matrices
> J. Liu, Z. Li, J. Yang
> 
> [![DOI:10.1063/5.0054822](https://img.shields.io/badge/DOI-10.1063/5.0054822-blue.svg)](https://doi.org/10.1063/5.0054822)
> 
>> 
>> The electronic structure problem is one of the most appealing applications of quantum computing. To simulate the electronic structure properties of molecules and solids, quantum algorithms, such as quantum phase estimation (QPE) and variational quantum eigensolver (VQE) had been proposed for solving the Schrödinger equation on quantum hardware. Quantum algorithms offer a potentially exponential speedup of simulating many-electron systems over classical methods.
>> 

> ### O(N³) Measurement Cost for Variational Quantum Eigensolver on Molecular Hamiltonians
> P. Gokhale, O. Angiuli, Y. Ding, K. Gui, T. Tomesh, M. Suchara, M. Martonosi, F. T. Chong
> 
> [![DOI:10.1109/TQE.2020.3035814](https://img.shields.io/badge/DOI-10.1109/TQE.2020.3035814-blue.svg)](https://doi.org/10.1109/TQE.2020.3035814)
> 
>> 
>> Quantum computational chemistry has been a long targeted problem on the classical computer. Due to the limits of classical computing resources ... The way to achieve chemical accuracy (1 kcal/mol) is to use full configuration interactions (CIs), which considers all necessary orbitals. Classically, this will generally require exponential runtime. On the other hand, quantum computation is able to encode an exponential amount of molecular information into a polynomial number of qubits and thereby achieve full CI in polynomial time.
>> 

> ### Polynomial-time quantum algorithm for the simulation of chemical dynamics
> I. Kassal, S. P. Jordan, P. J. Love, M. Mohseni, A. Aspuru-Guzik
> 
> [![DOI:10.1073/pnas.0808245105](https://img.shields.io/badge/DOI-10.1073/pnas.0808245105-blue.svg)](https://doi.org/10.1073/pnas.0808245105)
> 
>> 
>> An alternative way to compute a potential energy surface would be to embed an on-the-fly calculation of electronic structure in the quantum algorithm and thus avoid a classically precomputed fit. This can be done efficiently because electronic structure calculations can be performed in polynomial time on quantum computers. Hence, the quantum circuit 𝒱 would be replaced by a black box containing the efficient quantum version of the full configuration interaction (FCI) procedure.
>> 

> ### How will quantum computers provide an industrially relevant computational advantage in quantum chemistry?
> V. E. Elfving, B. W. Broer, M. Webber, J. Gavartin, M. D. Halls, K. P. Lorton, A. Bochevarov
> 
> [![DOI:10.48550/arXiv.2009.12472](https://img.shields.io/badge/DOI-10.48550/arXiv.2009.12472-blue.svg)](https://doi.org/10.48550/arXiv.2009.12472)
> 
>> 
>> Even though an exponential speedup of quantum chemical calculations is theoretically expected on quantum hardware, a significant obstacle to consider is the enormous prefactor to the polynomial runtime of quantum computational algorithms.
>> 

> ### Quantum computing applied to calculations of molecular energies: CH2 benchmark
> L. Veis, J. Pittner
> 
> [![DOI:10.1063/1.3503767](https://img.shields.io/badge/DOI-10.1063/1.3503767-blue.svg)](https://doi.org/10.1063/1.3503767)
> 
>> 
>> It was shown in [Aspuru-Guzik *et al.*, Science 309, 1704 (2005)] that they, if available, would be able to perform the full configuration interaction (FCI) energy calculations with a polynomial scaling. This is in contrast to conventional computers where FCI scales exponentially.
>> 

> ### Nonunitary operations for ground-state calculations in near-term quantum computers
> G. Mazzola, P. J. Ollitrault, P. K. I. Barkoutsos, I. Tavernelli
> 
> [![DOI:10.1103/PhysRevLett.123.130501](https://img.shields.io/badge/DOI-10.1103/PhysRevLett.123.130501-blue.svg)](https://doi.org/10.1103/PhysRevLett.123.130501)
> 
>> 
>> Solving quantum many-body and electronic structure problems is one of the most anticipated applications of quantum computers, in view of the exponential speed-up that can be achieved compared to classical simulations ...
The accuracy of this approach is demonstrated numerically in finding energies of entangled ground states of many-body lattice models.
>> 

> ### Simulating periodic systems on a quantum computer using molecular orbitals
> J. Liu, L. Wan, Z. Li, J. Yang
> 
> [![DOI:10.1039/B804804E](https://img.shields.io/badge/DOI-10.1039/B804804E-blue.svg)](https://doi.org/10.1039/B804804E)
> 
>> 
>> Simulating a quantum system is more efficient on a quantum computer than on a classical computer. The time required for solving the Schrödinger equation to obtain molecular energies has been demonstrated to scale polynomially with system size on a quantum computer, in contrast to the well-known result of exponential scaling on a classical computer.
>> 

> ### Exact electronic states with shallow quantum circuits through global optimisation
> H. G. A. Burton, D. Marti-Dafcik, D. P. Tew, D. J. Wales
> 
> [![DOI:10.48550/arXiv.2207.00085](https://img.shields.io/badge/DOI-10.48550/arXiv.2207.00085-blue.svg)](https://doi.org/10.48550/arXiv.2207.00085)
> 
>> 
>> Quantum computers promise to revolutionise electronic simulations by overcoming the exponential scaling of many-electron problems ... Highly accurate numerical simulations on strongly correlated molecules, including water and molecular nitrogen, and the condensed-matter Hubbard model, demonstrate that our algorithm reliably advances the state-of-the-art, defining a new paradigm for quantum simulations featuring strong electron correlation.
>> 

> ### Qubit coupled cluster method: a systematic approach to quantum chemistry on a quantum computer
> I. G. Ryabinkin, T. C. Yen, S. N. Genin, A. F. Izmaylov
>
> [![DOI:10.1021/acs.jctc.8b00932](https://img.shields.io/badge/DOI-10.1021/acs.jctc.8b00932-blue.svg)](https://doi.org/10.1021/acs.jctc.8b00932)
>
>>
>> Computational cost of the exact numerical solution of eq 1 scales exponentially with the size (e.g., the number of electrons) of the system on a classical computer. To address this issue without introducing approximations, it was proposed to employ a quantum computer, which may solve the problem with polynomial scaling of computational cost with the system size.
>>

> ### Quantum computing enhanced computational catalysis
> V. von Burg, G. H. Low, T. Häner, D. S. Steiger, M. Reiher, M. Roetteler, M. Troyer
>
> [![DOI:10.1103/PhysRevResearch.3.033055](https://img.shields.io/badge/DOI-10.1103/PhysRevResearch.3.033055-blue.svg)](https://doi.org/10.1103/PhysRevResearch.3.033055)
>
>>
>> Quantum computing has the potential to efficiently solve some computational problems that are exponentially hard to solve on classical computers. Among these problems, one of the most prominent cases is the calculation of quantum electronic energies in molecular systems.
>>

