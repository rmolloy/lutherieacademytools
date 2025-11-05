# 4DOF Acoustic Guitar Model & Delta-Recipe Solver
**© 2025 Rick Molloy — Celestial Instruments**

This repository implements a calibrated four-degree-of-freedom (4-DOF) acoustic-guitar model based on Gore-style modal coupling.  
It visualizes the interaction of **Air, Top, Back, and Rim modes**, showing coupled responses and parameter sensitivity.

### Current Version
The **What-If Simulator** (shown below) already allows direct manipulation of mass, stiffness, damping, and air parameters with live frequency-response updates.  
It’s designed as the forward-model foundation for the **Delta-Recipe Solver** — an upcoming inverse solver that:

1. Fits the 4-DOF model to a measured guitar response or tap-test data.  
2. Computes **2–3 practical delta recipes** (in plain English) to reach user-defined modal-frequency targets.  
3. Explains each move’s rationale, expected frequency shifts, and trade-offs.

> Public disclosure date: **2025-11-05**  
> Licence: MIT — attribution required (“© Rick Molloy”).

### Screenshot
*(Example UI — baseline vs. What-If delta)*  
![Current Implementation](docs/images/4dof-solver-ui.png)

### Roadmap
- [x] Forward 4-DOF solver and What-If visualization  
- [ ] Inverse solver: fit existing guitars and compute delta recipes  
- [ ] Plain-language recipe generator and sensitivity cards  
- [ ] Documentation and white-paper (v1)

---

**Attribution Reminder**  
If you build on or publish results from this repository, please cite:  
> *Molloy, R. (2025). 4-DOF Delta-Recipe Solver for Acoustic Guitars.*  
> GitHub repository https://github.com/[your-repo-path]
