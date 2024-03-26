# viral-saltations-in-silico

This simulation is a simple first step that aims to depict viral evolution once the virus has infected infected a new host. It assumes:

1. Host/environment selection pressures are constant
2. SARS-CoV-2 will never be controlled and thus will evolve indefinitely.
3. The virus stays in one, spatially implicit location with unbounded available space, and does not move to other locations, i.e. body compartments.

The purpose of this simulation is to practice SLiM syntax while also tinkering with some of the core settings governing how the virus will evolve within-host, e.g., the deleteriousness and beneficialness of mutations, the distributions mutation effects are drawn from, how recombination will need to work and how frequent it is, carrying capacity for density-dependent fitness scaling, etc.

Eventually, the code here will be subsumed by a more expansive simulation that depicts bottlenecked viral populations migrating to new hosts, each with their own distributions of mutation effects and distributions. Some of these hosts will have consistently weak selection on deleterious alleles--or perhaps exceptionally strong selection for beneficial alleles--which may bring about a pattern similar to the SARS-CoV-2 phylogeny.
