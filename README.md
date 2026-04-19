# alpha-td-rei

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-td-rei/blob/main/notebooks/alpha_td_rei.ipynb)

> TD Range Expansion Index (REI) alpha signal

> The TD REI measures directional range expansion relative to 5 bars prior. When REI crosses above +40 the market is expanding upward — stay long while REI remains above 0. REI below -40 signals downward expansion — stay short while REI is negative. The contraction zone near 0 keeps the system out of choppy, undirected markets.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | L7/S7 signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity (REI period, threshold) |
| 7 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

