# Enhancing Teaching with MATLAB – University of San Agustin

Workshop materials for faculty in **Chemical, Civil, and Mechanical Engineering** at the University of San Agustin. The workshop shows how MathWorks tools can modernize engineering curricula, from low-code MATLAB workflows to automated assessment and Generative AI in the classroom.

## Workshop Overview

### Part 1 – Enhancing Teaching and Learning with MATLAB
- **MATLAB Fundamentals** – The MATLAB environment, Live Scripts, and low-code tools (Live Tasks, apps) that speed up engineering work and reporting.
- **Online Training Services (OTS)** – Self-paced learning for students and faculty.
- **MATLAB Course Designer** – Designing learning activities and assessments.
- **MATLAB Grader** – Scalable, automated grading of student code.
- **Generative AI & MATLAB Copilot** – Practical ways to adapt to AI in teaching and put it to use.

### Part 2 – Domain Tracks
| Track | Topic | Folder |
|---|---|---|
| Chemical Engineering | Thermal analysis and process control – economic MPC of an ethylene oxide reactor | `ChemicalEngineering/` |
| Civil Engineering | Mechanics of materials – beam bending and deflection | `CivilEngineering/` |
| Mechanical Engineering | Thermal systems – house heating model in Simulink | `MechanicalEngineering/` |

Each track comes with a **Worksheet** version (for participants) and a **Solution** version (for instructors).

## Repository Structure
```
├── main.mlx                          # Workshop entry point
├── MATLABandSimulinkFundamentals/
│   ├── Enhance Teaching and Learning with MATLAB/
│   │   ├── MATLAB Fundamentals/      # Getting started, basics, data cleaning
│   │   ├── GenAI Exercises/          # MATLAB Copilot hands-on activities
│   │   └── *.pptx                    # Course Designer, Grader, GenAI slides
│   ├── Data Analysis/                # Simulink car model hands-on
│   └── SimulinkFundamentals.pptx
├── ChemicalEngineering/
│   └── EconomicMPCControlOfEOExample/
├── CivilEngineering/                 # Open MechanicsOfMaterials.prj
│   ├── Worksheet/
│   └── Solution/
├── MechanicalEngineering/
│   ├── Worksheet/
│   └── Solution/
└── AI for Engineering/               # Two-day AI workshop (ML, DL, Simulink)
```

## Requirements
- MATLAB and Simulink (R2024b or later recommended)
- Symbolic Math Toolbox (Civil Engineering track)
- Model Predictive Control Toolbox (Chemical Engineering track)
- MATLAB Copilot access (GenAI exercises)

To check which products you have installed, run `ver` in MATLAB.

## Getting Started
1. Download or clone this repository.
2. Open MATLAB and go to the repository folder.
3. Open `main.mlx` to start. For the Civil Engineering track, open `CivilEngineering/MechanicsOfMaterials.prj`.
4. Run each Live Script one section at a time.

## Resources
- [MATLAB Onramp](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted)
- [MATLAB Grader](https://www.mathworks.com/products/matlab-grader.html)
- [MathWorks Teaching Resources](https://www.mathworks.com/academia/educators.html)

## Acknowledgments
Some of the curriculum modules come from the [MathWorks Teaching Resources](https://github.com/MathWorks-Teaching-Resources) collection. See each module's `LICENSE.md` for its license terms.
