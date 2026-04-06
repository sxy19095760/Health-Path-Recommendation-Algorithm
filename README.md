# Health Path Recommendation Algorithm

This repository provides the implementation of the algorithm proposed in:

**"Health Path Recommendation Algorithm Based on Multi-Factor Optimisation for Diverse User Needs in Urban Health Activities"**

---

## Overview

This project presents a health-oriented path recommendation algorithm that generates and ranks urban walking/running routes based on multiple environmental and spatial factors.

The workflow includes:
1. Path generation  
2. Attribute extraction  
3. Multi-factor scoring and ranking  

The system is implemented using **Rhino 7 + Grasshopper**, with embedded **C# scripts**.

---

## How to Run

A detailed step-by-step guide (with figures) is available here:

👉 **[User Guide (PDF)](docs/user_guide.pdf)**

Quick steps:
1. Open `mapping.3dm` in Rhino 7  
2. Open `algorithm.gh` in Grasshopper  
3. Follow the guide to generate and evaluate paths  

---

## Repository Structure

- `rhino_grasshopper/` → Rhino model (`.3dm`) + Grasshopper workflow (`.gh`)  
- `results_example/` → sample outputs  
- `docs/` → user guide  

---

## Reproducibility

- Full workflow provided (`.gh`)  
- Example data and outputs included  
- Step-by-step guide provided  

---

## Notes

- The input data is embedded within the Rhino file (`.3dm`)  
- Preprocessed data generated from *Component 0* is provided in `results_example/output.csv`  


---

## Code Availability

All code and materials required to reproduce the results are available in this repository.
