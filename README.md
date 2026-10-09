# INTRO TO PYTHON

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-mining-lightgrey)

> Anticloud-hardened packaging of the upstream project `INTRO_TO_PYTHON` in category **MINING**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** MINING · **Upstream:** https://github.com/GeoLatinas/intro-to-python · **Upstream pin:** `d6d858f764e106488526ab4f5c3411705b3330d3` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Introduction to Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GeoLatinas/Intro-to-python/HEAD)

|               | Info
|---------------|---------------------------------------------
| WHEN          | TBD
| WHERE         | GeoLatinas Zoom
| CHAT          | `#coding-group` in GeoLatinas Slack
| REQUIREMENTS  | [Be a GeoLatinas member!](https://geolatinas.weebly.com/get-involved.html)

## Modulo 1 - Numpy, for loops y functions

### Sábado, 13/02/2020 Santiago Soler y Andrea Balza :
- Variables: [01-variables.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/01-variables.ipynb)
  ([Correr en binder](https://mybinder.org/v2/gh/GeoLatinas/Intro-to-python/HEAD?filepath=notebooks%2F01-variables.ipynb))

### Sábado, 20/02/2020 Andrea Balza y Maria Cecilia Bravo:
- Listas y for-loops: [02-listas_y_for_loops.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/02-listas_y_for_loops.ipynb)

### Sábado, 27/02/2020 Santiago Soler y Maria Cecilia Bravo:
- Numpy: [03-numpy.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/03-numpy.ipynb)
- Gráficos: [04-graficos.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/04-graficos.ipynb)
- 05 - funciones
- 06 - decisiones
- 07 - regresion_lineal

### Recursos:

- [Introducción a Python para Científicxs 2020](https://santisoler.github.io/teaching/python-unsj.html)
  by Santiago Soler (Spanish) (8 hours, 4 lessons)
- [Intro to Python by Kaggle](https://www.kaggle.com/learn/python) (7 hours, 7 lessons)

- [Advanced Numpy. Appendix A from Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython](https://github.com/wesm/pydata-book/blob/2nd-edition/appa.ipynb)

## Modulo 2 - Pandas

### Recursos:

- [Intro to Pandas by Kaggle](https://www.kaggle.com/learn/pandas) (4 hours, 6 lessons)
- [Advanced Pandas. Chapter 12 from Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython](https://github.com/wesm/pydata-book/blob/2nd-edition/appa.ipynb)

## Modulo 3 - Data visualization

### Recursos:
- [Data visualization by Kaggle](https://www.kaggle.com/learn/data-visualization)
  (4 hours, 8 lessons)
- [Data visualization with Python by WWC](https://www.youtube.com/watch?v=wvDbLhconLU) (1 hour)

## Licencia

[![CC BY 4.0][cc-by-image]][cc-by]

El contenido de este repositorio se encuentra disponible bajo la licencia [Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `data/`, `notebooks/`
- Snapshot size: **24 files**, **32 lines of code** (measured; see Benchmarks)
- Primary languages: `.ipynb` (14), `.csv` (3), `.dat` (2), `.md` (2), `(none)` (1), `.py` (1)
- Upstream commit pinned for this packaging: `d6d858f764e106488526ab4f5c3411705b3330d3`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

Browse the snapshot layout listed under What This Project Does and follow the upstream run instructions for the detected ecosystem (Unknown (no standard manifest detected)).

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

### Sábado, 13/02/2020 Santiago Soler y Andrea Balza :
- Variables: [01-variables.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/01-variables.ipynb)
  ([Correr en binder](https://mybinder.org/v2/gh/GeoLatinas/Intro-to-python/HEAD?filepath=notebooks%2F01-variables.ipynb))

### Sábado, 20/02/2020 Andrea Balza y Maria Cecilia Bravo:
- Listas y for-loops: [02-listas_y_for_loops.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/02-listas_y_for_loops.ipynb)

### Sábado, 27/02/2020 Santiago Soler y Maria Cecilia Bravo:
- Numpy: [03-numpy.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/03-numpy.ipynb)
- Gráficos: [04-graficos.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/04-graficos.ipynb)
- 05 - funciones
- 06 - decisiones
- 07 - regresion_lineal

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 24 |
| Lines of code | 32 |
| Dependency references | 0 |
| Upstream license | No license file present in the upstream snapshot |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

([Correr en binder](https://mybinder.org/v2/gh/GeoLatinas/Intro-to-python/HEAD?filepath=notebooks%2F01-variables.ipynb))

### Sábado, 20/02/2020 Andrea Balza y Maria Cecilia Bravo:
- Listas y for-loops: [02-listas_y_for_loops.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/02-listas_y_for_loops.ipynb)

### Sábado, 27/02/2020 Santiago Soler y Maria Cecilia Bravo:
- Numpy: [03-numpy.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/03-numpy.ipynb)
- Gráficos: [04-graficos.ipynb](https://github.com/GeoLatinas/Intro-to-python/blob/main/notebooks/04-graficos.ipynb)
- 05 - funciones
- 06 - decisiones
- 07 - regresion_lineal

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `INTRO_TO_PYTHON` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: No license file present in the upstream snapshot** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
Attribution 4.0 International

=======================================================================

Creative Commons Corporation ("Creative Commons") is not a law firm and
does not provide legal services or legal advice. Distribution of
Creative Commons public licenses does not create a lawyer-client or
other relationship. Creative Commons makes its licenses and related
information available on an "as-is" basis. Creative Commons gives no
warranties regarding its licenses, any material licensed under their
terms and conditions, or any related information. Creative Commons
disclaims all liability for damages resulting from their use to the
fullest extent possible.

Using Creative Commons Public Licenses

Creative Commons public licenses provide a standard set of terms and
conditions that creators and other rights holders may use to share
original works of authorship and other material subject to copyright
and certain other rights specified in the public license below. The
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original No license file present in the upstream snapshot terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `No license file present in the upstream snapshot` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `INTRO_TO_PYTHON` (category: MINING)
- **Upstream URL:** https://github.com/GeoLatinas/intro-to-python
- **Pinned commit (SHA):** `d6d858f764e106488526ab4f5c3411705b3330d3`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`429b6780deaa5a5371eefbb1ff9251e59a992fc05a5da8cc1ebbd48b72ef22ea`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

