# wcraytor
GitHub profile README
# Bert Craytor · [@wcraytor](https://github.com/wcraytor)

** Software Engineer, Retired Appraiser **  
Pacifica, CA · [valuationengineer.com](https://valuation-engineer.com) · [journal.valuation-engineer.com](https://journal.valuation-engineer.com)

---

## About

I sit at the intersection of real estate valuation and applied statistics — forty-plus years of software engineering behind me, building tools that make appraisal methodology defensible, auditable, and reproducible.

My current focus is **ValEngr**, a polyglot valuation platform designed around my own [Residual Constraint Approach (RCA)](https://zenodo.org/search?q=Craytor) — a framework that derives market adjustments from MARS basis function contributions rather than direct paired-sale estimates.

---

## ValEngr Platform

**Stack:** Angular · FastAPI · PostgreSQL/PostGIS · SWI-Prolog · R · Python

| Layer | Purpose |
|---|---|
| **Prolog** | USPAP/UAD 3.6 compliance engine — regulatory logic as first-class code |
| **R / earth (MARS)** | Feature discovery and basis function construction |
| **R / glmnet** | Penalized regression tier on raw features |
| **R / mgcv** | Spatial smoothing, tensor products, mixed effects |
| **R / rgeoda** | SKATER spatial clustering |
| **Python / CNN–YOLO–SAM** | Computer vision pipeline for property photo classification |
| **FastAPI** | REST backend, report generation |
| **Angular** | Frontend |

---

## R Packages

| Package | Description | Status |
|---|---|---|
| [**earthUI**](https://CRAN.R-project.org/package=earthUI) | Shiny GUI for the `earth` (MARS) package | ✅ CRAN v0.1.3 |
| **glmnetUI** | Shiny GUI for `glmnet` penalized regression | 🔧 Development |
| **mgcvUI** | Shiny GUI for `mgcv` spline/GAM modeling | 🔧 Development |

---

## Research

- **Residual Constraint Approach (RCA)** — DOI on Zenodo. A methodology for deriving appraisal adjustments from regression model contributions, designed for USPAP-defensible and GSE-compliant reporting.
- Journal of Valuation Engineering: [journal.valuation-engineer.com](https://journal.valuation-engineer.com) (OJS 3.5)

---

## Technical Interests

- Regression methodology for hedonic valuation (MARS → glmnet → mgcv pipeline architecture)
- Logic programming for regulatory compliance (Prolog / USPAP / UAD rule encoding)
- Computer vision for property analysis (CNN / YOLO / SAM)
- Spatial econometrics (PostGIS, rgeoda, SKATER clustering)
- Local LLM deployment (Ollama / DeepSeek)
- Reproducible appraisal reporting (Quarto / LaTeX / Docker)

---

## Languages & Tools

```
R · Python · Prolog (SWI) · C++ · SQL / PostGIS
Angular · FastAPI · Docker / OrbStack
VS Code · RStudio · LaTeX / TeXstudio · DEVONthink
```

---

## Credentials

- **Certified General Real Estate Appraiser (Retired) ** — California
- **SRA Designated Member* — Appraisal Institute
- S-Corp: [Valuation Engineer](https://valuationengineer.com)

---

*Building the infrastructure for evidence-based appraisal.*
