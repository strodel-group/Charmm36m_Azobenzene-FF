# Charmm36m_Azobenzene-FF
Charmm36m force field with an extension for Azobenzene.
The force field is parameterized for either cis or trans and only differs in the definition of the C-N-N-C angle, which is set to 180° or 0° respectively.
We parameterized the interactions following the cgenff standard protocol [1] and refined the parameterization using data from QM/MM simulations [2], by fitting our parameters to reproduce the bond, angle, and dihedral angle distributions of the cis and trans states as obtained from QM/MM.

The PTH25-37_P4-mutant_withAzobenzene.itp file is the topology file used for simulations of the P4 mutation of the PTH<sub>25-37</sub> peptide as described in Paschold et al [3]. It can be used as a template to parameterize an AZO group and for cross-reference of the nomenclature in the force field.


[1] Vanommeslaeghe, K.; Hatcher, E.; Acharya, C.; Kundu, S.; Zhong, S.; Shim, J.; Darian, E.; Guvench, O.; Lopes, P.; Vorobyov, I. CHARMM general force field: A force field for drug‐like molecules compatible with the CHARMM all‐atom additive biological force fields. Journal of computational chemistry 2010, 31 (4), 671-690.

[2] Böckmann, M.; Peter, C.; Site, L. D.; Doltsinis, N. L.; Kremer, K.; Marx, D. Atomistic force field for azobenzene compounds adapted for QM/MM simulations with applications to liquids and liquid crystals. Journal of chemical theory and computation 2007, 3 (5), 1789-1802.

[3] Paschold, A.; Schäffler, M.; Miao, X.; Gardon, L.; Heise, H.; Röhr,M. I. S.; Ott, M.; Strodel, B; Binder, W. H. Photocontrolled peptides for reversible amyloid fibril formation. Not published yet.
