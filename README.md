# zx-homology-fault-equivalence

**Title:** From Fault Equivalent ZX Diagrams to Fault-Tolerant Maps for Spacetime Codes

**Author:** Tanishi Mishra

**Affiliation:** MSc, University of Oxford

**Date:** 10/22/2026

## Abstract

Fault-tolerant quantum computation relies on error-correcting codes to protect fragile quantum data from noise, but implementing these codes as physical circuits raises a subtle issue: circuits with the same logical behavior can differ in their fault-tolerant properties depending on how measurements are ordered and how the code is built. Spacetime subsystem codes address this by tracking each physical qubit and timestep as a distinct spacetime location. Multiple seemingly compatible notions of fault-tolerance have since been defined for these codes: diagrammatic and fault-tolerant maps. However, there is no formal account of whether they coincide. In this work, we show fault-equivalence does not imply the existence of fault-tolerant mapping since decoding is not necessarily preserved. We construct two circuit implementations that are fault-equivalent under ZX formalism and have a weak quasi-isomorphism between them along with distance preservation but do not preserve the decoding required for complete fault-tolerant mapping. We conjecture that the converse holds: fault-tolerant mapping does imply fault-equivalent diagrams. To generalize beyond existing weight-2 gauge-operator mappings, we develop a framework built on algebraic discrete Morse theory for constructing chain maps between spacetime complexes when weight-3 or higher gauge operators are involved, and prove these maps are valid weak quasi-isomorphisms, though distance or decoding need not be preserved. We further examine when the edge flip noise gauge group of a ZX diagram contains its phenomenological-noise counterpart, reducing this to a solvable linear system and verifying it across worked examples. We formalize a setting for when this is possible. Together, these results clarify the relationship between diagrammatic and fault-tolerant maps built from chain complexes based fault-equivalence for spacetime codes.

## Citation Format

T. Mishra, "From Fault Equivalent ZX Diagrams to Fault-Tolerant Maps for Spacetime Codes," preprint, 2026. Available at: https://github.com/tanishi-mishra/zx-homology-fault-equivalence

## BibTeX

```bibtex
@misc{mishra2026zxftmaps,
  author       = {Mishra, Tanishi},
  title        = {From Fault Equivalent {ZX} Diagrams to Fault-Tolerant Maps for Spacetime Codes},
  year         = {2026},
  note         = {Preprint},
  howpublished = {\url{https://github.com/tanishi-mishra/zx-homology-fault-equivalence}}
}
```
