## Jae Min Yoon

MS Bioinformatics student at Northeastern University (BS Pharmaceutical Sciences, MCPHS).
I work on single-cell perturbation data end to end: raw reads, analysis, modeling, and evaluation.

### Projects

**[NGSpipeline](https://github.com/jam-sudo/NGSpipeline)** · Nextflow DSL2, nf-core template

Perturb-seq raw-read pipeline: FASTQ to count matrices, per-cell guide assignment, and an analysis-ready h5ad.
- Validated on all 12 GEM groups of Replogle 2022 K562: 95.3 to 96.3% agreement with the authors' guide identities
- Byte-identical output across local Docker, SLURM Singularity, and a 12-sample SLURM run
- nf-test coverage, CI, versioned releases with a Zenodo DOI

**[ALIVE](https://github.com/jam-sudo/alive)** · Python

Preregistered, leakage-controlled evaluation for perturbation-response prediction on Replogle K562 Perturb-seq: an error-aware trust gate with a split-conformal error bound, scored once on a sealed cohort. Result: the error bound was valid; the gate did not beat its comparators. Ongoing work covers combinatorial perturbations (Norman K562 CRISPRa).

**[Sisyphus](https://github.com/jam-sudo/Sisyphus)** · Python

Topology-compiled PBPK model: the body as a 34-compartment typed directed multigraph with YAML-configured ODE assembly.
- Preprint: [ChemRxiv, doi:10.26434/chemrxiv.15004452](https://doi.org/10.26434/chemrxiv.15004452)

**Virtual Cell Challenge 2026** · in progress

Competing in the Arc Institute challenge on zero-shot perturbation prediction; a write-up of the approach and results will follow.

### Contact

[LinkedIn](https://www.linkedin.com/in/jae-min-yoon-b14491408)
