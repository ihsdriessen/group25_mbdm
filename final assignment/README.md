# IJssel River Flood Risk Policy Modeling – Final Assignment

This project supports **Waterboard Veluwe** in designing climate-resilient and nature-based strategies to manage flood risks along the IJssel River. The work explores and evaluates a range of policy strategies through simulation, scenario discovery, and robust decision-making under deep uncertainty.

## Objective

To determine effective flood risk management strategies for Waterboard Veluwe that:
- Minimize expected annual flood damage.
- Maintain cost-efficient investment in dike reinforcements.
- Promote nature-based solutions under the Room for the River (RfR) program.
- Align with the priorities of diverse stakeholders.

## Tools and Techniques

- **Exploratory Modeling Workbench (EMW)**: Simulation and uncertainty analysis.
- **PRIM (Patient Rule Induction Method)**: Scenario discovery.
- **Sobol & Extra Trees**: Sensitivity analysis.
- **Multi-objective Robust Decision Making (MORDM)**: Robust optimization.

## Repository Structure

```
final assignment/
├── data                            # data used
├── dike_model_function.py          # Main model logic
├── dike_model_simulation.py        # Run simulation experiments
├── dike_model_optimization.py      # Perform robust optimization
├── funs_dikes.py                   # Dike model utilities
├── funs_economy.py                 # Economic calculations
├── funs_generate_network.py        # Network and planning structure
├── funs_hydrostat.py               # Hydrological models
├── MORDM.ipynb                     # MORDM of waterboard Veluwe
├── MORDM_DC.ipynb                  # MORDM of dikering Doesburg & Cortenoever
├── MORDM_OVERIJSSEL.ipynb          # MORDM of municipality Overijssel
├── MORDM_ZUTPHEN.ipynb             # MORDM of dikering Zutphen
├── OpenExploration.ipynb           # Open exploration 
├── Problem Formulations.ipynb      # Problem formulations show model
├── problem_formulation.py          # Problem formulations make model (not used)
├── problem_formulation2.py         # Problem formulations make model
├── README.md
├── ScenarioDiscovery.ipynb         #Scenario Discovery
├── SensitivityAnalysis.ipynb       #Sensitivity analysis
└──dike_open_exploration_results.tar.gz # Archived simulation results
```

## How to Run

1. **Install dependencies** (recommended in a virtual environment):

```bash
pip install ema_workbench numpy pandas matplotlib seaborn scipy
```

2. **Run simulations**:

```bash
python dike_model_simulation.py
```

3. **Run optimization**:

```bash
python dike_model_optimization.py
```

## Stakeholder Context

The model incorporates alternative perspectives from:
- **Waterboard Veluwe**: Favoring upstream RfR and biodiversity.
- **Dikering Zutphen**: Urban safety, heritage preservation.
- **Doesburg & Cortenoever**: Agricultural sustainability.
- **Province of Overijssel**: Biodiversity and cost-sharing focus.

## License and Acknowledgments

Academic group project for the EPA course by Group 25:
- Larissa Amirjalali
- Inez Driessen
- Romy Huizer
- Evalie van Oijen

This work builds on the Dutch "Room for the River" policy framework using state-of-the-art modeling and policy analysis.

---


