# HCR_eval

Bering Sea pollock-like age-structured simulation exploring steepness, reference points, harvest control rules, and sensitivity analyses.

## Contents

- `pollock_simulation.qmd`: Quarto report with all analysis, figures, and tables.
- `pollock_simulation.html`: Rendered standalone HTML output (embedded resources).
- `R/pollock_simulation.R`: Model and helper functions.

## Render

```sh
quarto render pollock_simulation.qmd
```

## Notes

- HTML output is configured to be standalone via embedded resources.
- The model initializes simulations at Fmsy equilibrium by default.
