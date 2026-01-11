
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![License: Dual License](https://img.shields.io/badge/license-Dual--License-blue)
)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](#)
[![Stars](https://img.shields.io/github/stars/tlcagford/Primordial-Photon-Dark-Photon-Entanglement.svg)](https://github.com/tlcagford/Primordial-Photon-Dark-Photon-Entanglement/stargazers)
[![Issues](https://img.shields.io/github/issues/tlcagford/Primordial-Photon-Dark-Photon-Entanglement.svg)](https://github.com/tlcagford/Primordial-Photon-Dark-Photon-Entanglement/issues)
[![Last Commit](https://img.shields.io/github/last-commit/tlcagford/Primordial-Photon-Dark-Photon-Entanglement.svg)](https://github.com/tlcagford/Primordial-Photon-Dark-Photon-Entanglement/commits)
[![Repo Size](https://img.shields.io/github/repo-size/tlcagford/Primordial-Photon-Dark-Photon-Entanglement.svg)](#)

# Primordial Photon–Dark Photon Entanglement
https://cosmic-entanglement-visualizer-f4f21576.base44.app/Dashboard

A research and analysis framework for testing the **Photon–Dark Photon Entanglement Hypothesis**, analyzing astronomical imaging data, and generating reproducible physics validation results using HST, JWST, and other observatory FITS products.

---

## 🚀 Overview
This repository provides:

- **Physics Validation Tests** that compute predicted P–D entanglement observables.
- **Expected Numerical Results** for cross‑checking model predictions.
- **Automated pipelines** for running analyses on clusters (e.g., *Abell 1689*) and other astrophysical targets.
- **Jupyter notebooks** for full end‑to‑end scientific workflows.
- **Data ingestion tools** for MAST/HST/JWST FITS downloads.

---

## 📂 Repository Structure

```
Primordial-Photon-Dark-Photon-Entanglement/
├── Physics_Validation_Tests.py
├── Expected_Numerical_Results.py
├── utils/
│   ├── preprocessing.py
│   ├── fits_tools.py
│   └── visualization.py
├── notebooks/
│   ├── Photon_DarkPhoton_Cluster_Analysis.ipynb
│   └── JWST_COSMOS_Advanced.ipynb (optional)
└── README.md
```
Fuzzy Dark Matter (FDM) Derivation Summary

consolidated:
1. Relativistic Foundation

    Action:

S=∫d4x−g[12gμν∂μϕ∂νϕ−12m2ϕ2]+Sgravity
S=∫d4x−g
​[21​gμν∂μ​ϕ∂ν​ϕ−21​m2ϕ2]+Sgravity​

    Klein-Gordon Equation:

□ϕ+m2ϕ=0,□=gμν∇μ∇ν
□ϕ+m2ϕ=0,□=gμν∇μ​∇ν​
2. Non-Relativistic Limit

    Field decomposition:

ϕ(x,t)=12m[ψ(x,t)e−imt+ψ∗(x,t)eimt]
ϕ(x,t)=2m
​1​[ψ(x,t)e−imt+ψ∗(x,t)eimt]

    Schrödinger equation:

i∂tψ=−12m∇2ψ+mΦψ
i∂t​ψ=−2m1​∇2ψ+mΦψ
3. Self-Gravity Closure

    Poisson equation:

∇2Φ=4πGρ=4πG∣ψ∣2
∇2Φ=4πGρ=4πG∣ψ∣2

    Full Schrödinger-Poisson system (ℏ=1):

i∂tψ=−12m∇2ψ+Φψ,∇2Φ=4πG∣ψ∣2
i∂t​ψ=−2m1​∇2ψ+Φψ,∇2Φ=4πG∣ψ∣2
4. Two-Field FDM (Light-Dark Duality)

    Combined wavefunction:

ψ=ψt+ψdeiΔϕ
ψ=ψt​+ψd​eiΔϕ

    Coupled evolution (weak mixing ε≪1):

i∂tψt=−12mt∇2ψt+(Φt+ϵΦd)ψt
i∂t​ψt​=−2mt​1​∇2ψt​+(Φt​+ϵΦd​)ψt​
i∂tψd=−12md∇2ψd+(Φd+ϵΦt)ψd
i∂t​ψd​=−2md​1​∇2ψd​+(Φd​+ϵΦt​)ψd​

    Interference density:

ρ=∣ψ∣2=∣ψt∣2+∣ψd∣2+2ℜ(ψt∗ψdeiΔϕ)
ρ=∣ψ∣2=∣ψt​∣2+∣ψd​∣2+2ℜ(ψt∗​ψd​eiΔϕ)

    Fringe spacing (plane wave approximation):

λ=2π∣Δk∣≈hmv
λ=∣Δk∣2π​≈mvh​

where vv is relative velocity between sectors.
5. Solitonic Solutions

    Stationary ansatz:

ψ=ρ(r)e−iμt
ψ=ρ(r)
​e−iμt

    Stationary equations:

μρ=−12m∇2ρ+Φρ,∇2Φ=4πGρ
μρ
​=−2m1​∇2ρ
​+Φρ
​,∇2Φ=4πGρ

    Ground state core density scaling:

ρc∝m2G
ρc​∝Gm2​
Key Physical Insights:

    FDM mass scale: m∼10−22 eVm∼10−22eV gives de Broglie wavelength comparable to dwarf galaxies (~kpc)

    Wave behavior: Schrödinger-Poisson system describes coherent, self-gravitating Bose condensate

    Two-field interference: Creates observable density fringes with spacing λ ∝ 1/(mΔv)

    Solitonic cores: Naturally form stable, non-fragmenting structures (explains dark matter cores in galaxies)

    Experimental relevance: For comet-scale observations (like 3I/ATLAS), fringe spacing can be tuned to match observed angular offsets (~arcseconds)

Applications:

    Galactic scale: Solves cusp-core problem in dwarf galaxies

    Laboratory/SS scale: Interference patterns could manifest as periodic forces or density modulations

    Dark photon connection: Two-field FDM provides framework for light-dark sector interactions

This derivation establishes FDM as a viable wave-based dark matter candidate with testable phenomenological consequences across scales.
---

## 🧪 Running Analyses

### **Quickstart Example (Abell 1689)**

```bash
python run_abell1689_demo.py
```

Outputs include:
- Processed maps
- Numerical validation results
- Metadata JSON
- PNGs of reconstructed entanglement signals

A full Jupyter notebook version is included in:
```
notebooks/Photon_DarkPhoton_Cluster_Analysis.ipynb
```

---

## 📥 Data Sources Supported
- **Hubble Space Telescope (HST)** via **MAST**
- **JWST NIRCam/MIRI**, including COSMOS-Web
- **MeerKAT / SKA FITS** (optional extensions)
- Any standard FITS file with WCS metadata

---

## 📊 Outputs
The pipeline produces:
- Entanglement maps
- Numerical validation tables
- Model deviation/error metrics
- Reproducible metadata packages

---

## ⚙️ Installation

```bash
git clone https://github.com/tlcagford/Primordial-Photon-Dark-Photon-Entanglement
cd Primordial-Photon-Dark-Photon-Entanglement
pip install -r requirements.txt
```

---

## 📝 Licensing
This project uses a **Dual-License model**:

- **Commercial License**: Required for for-profit, enterprise, or corporate use.
- **Open Academic & Personal License**: Free for academic research, public study, and personal exploration.

See the `LICENSE` file for details.

Badge:
```
![License: Dual License](https://img.shields.io/badge/license-Dual--License-blue)
```

---

## 🤝 Contributing
Pull requests are welcome.
For major changes, open an issue to discuss your proposal.

A Contributor License Agreement (CLA) may be required for future releases.

---

## 📫 Contact
Author: **Tony E. Ford**  
Independent Researcher / Astrophysics & Quantum Systems

