# Stability of the stationary state in networks of phase oscillators

This repository contains the code for my Physics Licenciatura Thesis (Instituto Balseiro, <year>):
**"<Thesis title>"**, by <Name Surname>. Supervisor: <Name Surname>.

## Contents

| Notebook | Description |
|---|---|
| `ConectividadGenericaDinamicaRedGenerica.ipynb` | Event-driven simulations of networks of N phase oscillators with a generic phase response curve (PRC): QIF, SNIC–SNL and tent. Synaptic weights follow a distribution Ω(ω). The notebook computes the empirical density ψ_N(φ,t), the Fourier coefficients s_k(t) and the power spectrum P(ν). |
| `SolucionesEcTrascendentalEstabilidadEstacionario.ipynb` | Stationary density ρ_e(φ) of the continuity equation, and numerical solution of the transcendental equation for the linear stability of the stationary state (purely imaginary roots). It covers the QIF and the symmetric tent PRCs. |

The code comments and explanations inside the notebooks are in Spanish.

## Requirements

Python 3.10 or newer. Install the dependencies with:

```
pip install -r requirements.txt
```

## How to use

Open the notebooks with Jupyter or VS Code and run all cells in order.
In the simulation notebook, the first cells define the models and functions that the later cells use, so they must run first.

## Units

The model uses arbitrary units:

- **u.v.**: arbitrary unit of membrane potential, used for the synaptic weights ω_ij and their mean μ_ω.
- **u.t.**: arbitrary unit of time, fixed by the free phase velocity v = 2 rad/u.t.

The phase φ is measured in radians, so the PRC Z(φ) has units of rad/u.v.
See the units section at the start of each notebook for the full list.

## How to cite

If you use this code, please cite the thesis and this repository.
Click **"Cite this repository"** on the right side of this page, or see `CITATION.cff`.

## License

This project is under the MIT License. See `LICENSE` for details.
