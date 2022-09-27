# Simulation Neutron beam in a slab shield using the Method of Monte Carlo

Is the classic problem of a neutron beam in a shield with two layers of slabs. With constant cross sections, with the first slab having a 2 length of MFP and being scattering only, and the second slab having a length of 1 MFP being purely absorption.  With the neutron source centered under the scattering slab, as shown in Figure.

<img src="/image/experimental_Illustration.png" alt="Alt text" title="Optional title">


The neutron when inside a material can be absorbed, reflected, or passed without having any interaction
with the atoms of the material, as shown in Figure.

<img src="/image/interaction.png" alt="Alt text" title="Optional title">

When it interacts with the atoms of the material, and it is not absorbed, its position will be changed randomly,
to calculate the next direction of the neutron, which is equivalent to finding a random point on the surface of
a unitary sphere.


As previously described the first slab is scattering, so no neutrons will be absorbed, therefore there are only
two options that will be transmitted or reflected as in figure.

 <img src="/image/interacaoEspalhamento.png" alt="Alt text" title="Optional title">

Flowchart of the program , for better understanding of the modeling.

<img src="/image/fluxograma.png" alt="Alt text" title="Optional title">
