# Henipavirus Antibody Escape Model

A computational framework for predicting antibody escape across the
henipavirus family using published deep mutational scanning (DMS) data
and structural features.

## Background

Nipah virus and other henipaviruses are high-consequence zoonotic
pathogens. The receptor-binding protein (RBP) is the primary target of
neutralizing antibodies. Deep mutational scanning has mapped how
mutations in the Nipah Malaysia RBP affect antibody escape (Larsen et
al., Cell 2025), but this has not been systematically extended to other
henipaviruses. This project builds a reusable pipeline to link
structural features to escape propensity and extrapolate predictions
across the family.

## Pipeline (planned)

1. Download DMS escape scores and PDB structures.
2. Calculate per-residue structural features (SASA, distance to receptor
   interface, antibody footprint membership).
3. Train a simple model linking features to escape scores.
4. Extrapolate to homologous positions in other henipaviruses.
5. Output ranked lists of conserved escape-resistant positions versus
   strain-specific vulnerabilities.

## Data Sources

- Nipah DMS escape scores: https://github.com/dms-vep/Nipah_Malaysia_RBP_DMS
- PDB structure 2VSM: https://www.rcsb.org/structure/2VSM

## Installation

(To be added once the environment is set up.)

## Usage

(To be added once scripts are written.)

## Repository Structure

- `data/` — input data (download separately; see Data Sources)
- `scripts/` — analysis scripts
- `results/` — output tables and figures
- `docs/` — project plan and notes

## Status

Early development. No scripts or results yet.

## License

MIT
