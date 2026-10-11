# pcaanalysismrpo

SARS-CoV-2 Mpro conformational changes induced by covalently bound ligands.

## Background

The main protease (Mpro) of SARS-CoV-2 processes the viral polyprotein and is a key antiviral target. Many Mpro crystal structures with different ligands are available, but static structures may underestimate ligand-induced fit. This work uses molecular dynamics simulations to examine how ligand binding influences Mpro dynamics and the inhibitory mechanism, bridging the gap between static crystals and protein dynamics to support the discovery of new small-molecule inhibitors.

## Contents

| File | Description |
|---|---|
| `PCA-mpro-gmf.ipynb` | PCA of Mpro MD trajectories with different covalent ligands |

## Requirements

Python 3 with Jupyter and the libraries listed below. Trajectories and
Schrödinger Suite outputs are **not** included in this repository.

```bash
pip install jupyter numpy pandas matplotlib seaborn
```

## Author

**Glaucio Monteiro Ferreira** — Research Associate, Institute of Chemistry, University of São Paulo (IQ-USP) · [LIBNM · Ferreira Lab](https://ferreiralab.com.br) · [ORCID](https://orcid.org/0000-0002-1952-9428) · [FAPESP profile](https://bv.fapesp.br/pt/pesquisador/703612/glaucio-monteiro-ferreira/) · [gmf@usp.br](mailto:gmf@usp.br)
