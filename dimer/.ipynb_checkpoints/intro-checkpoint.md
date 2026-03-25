# A pair of identical two-level systems



In this chapter, we consider a pair of identical quantum dots.   The total system is described by four-dimensional Hilbert space and the density matrix is $4 \times 4$.  If the two QDs are completely independent, then the matrix is block diagonal with a pair of $2 \times 2$ submatrices.  There is no off-diagonal element across the two QDs.  In experiment, two photons may be detected simultaneously but that is purely coincidence.  

There are two possible ways that the two QDs  are coupled.  First of all, if two QDs directly interact through some mechanism such as the dipole-dipole interaction, the Hamiltonian of the system contains an interaction term $H_{int}$.  The net Hamiltonian looks like
$$
H_{s} = H_{1} + H_{2} + H_{int}
$$
where $H_i$ is the Hamiltonian for the $i$-th QD.

Secondly, two QDs can collectively interact with the same radiation fields, which causes superradiance/subradiance.   That effect is particularly strong if the distance between the QDs is shorter than the wave length of the photons.   Within the formulation of quantum master equation, such interaction can be expressed as a new type of dissipator
$$
\mathcal{D}(L_i,L_j) \rho = \gamma_{ij} \left(L_{j} \rho L_{i}^{\dagger} - \frac{1}{2} \{L_{i}^{\dagger} L_{j}, \rho\}\right)
$$
WHen $i=j$, we have the regular dissipator for the individual QD.  The net dissipators can be written as $\sum_{i,j} \mathcal{D}(L_{i},L_{j})$.

In the following sections, first we develop a model Hamiltonian and dissipators.  Then, we solve the master equation.   When analytical calculation is difficult, we resort to numerical methods. (We use `QuTip` .)  Even for numerical approach, some mathematical preparation is necessary.  For example, the choice of basis set is very important.
$$

$$


  