# [Paper title]

# Exact Statistics and Tight Approximations for RIS-Assisted Communications in Generalized Fading Environments

[![DOI](https://zenodo.org/badge/1451847058.svg)](https://doi.org/10.5281/zenodo.24093227)

Code accompanying the conference paper:

> M. C. Luna Alvarado, C. R. Nogueira da Silva, N. Simmons, P. C. Sofotasios,
> S. L. Cotton, and M. D. Yacoub, "Exact Statistics and Tight Approximations
> for RIS-Assisted Communications in Generalized Fading Environments," in
> *Proc. 2024 IEEE 100th Vehicular Technology Conference (VTC2024-Fall)*, 2024.
> DOI: [10.1109/VTC2024-Fall63153.2024.10757729](https://doi.org/10.1109/VTC2024-Fall63153.2024.10757729)

## Contents

| File | Description | Figures in the paper |
|---|---|---|
| `ABER-plots.nb` | Average symbol error rate (ASER) of the RIS-assisted system with direct link, under κ-µ fading (L = 4) and extended η-µ fading (L = 3), together with the asymptotic ASER | Figs. 1 and 2 |

The notebook implements the α-µ-based approximations for the κ-µ and extended
η-µ fading models, the resulting ASER expressions and the closed-form
asymptotic expressions derived in the paper, and generates both figures.
[The analytical results are compared against Monte Carlo simulations with
10^6 samples included in the notebook.]

## Requirements

- Wolfram Mathematica [version, 13]

## Usage

Open `ABER-plots.nb` in Mathematica and evaluate all cells
(*Evaluation → Evaluate Notebook*). Figs. 1 and 2 are generated at the end
of the notebook.

## Citation

If you use this code, please cite the paper above:

```bibtex
@inproceedings{LunaAlvarado2024VTC,
  author    = {Luna Alvarado, Maria Cecilia and Nogueira da Silva, Carlos Rafael and Simmons, Nidhi and Sofotasios, Paschalis C. and Cotton, Simon L. and Yacoub, Michel Daoud},
  title     = {Exact Statistics and Tight Approximations for {RIS}-Assisted Communications in Generalized Fading Environments},
  booktitle = {Proc. 2024 IEEE 100th Vehicular Technology Conference (VTC2024-Fall)},
  year      = {2024},
  doi       = {10.1109/VTC2024-Fall63153.2024.10757729}
}
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
