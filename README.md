# gravity-inversion-from-scratch

Gravity inversion in Python, built up step by step from first principles.
I'm an MSc Tech. Applied Geophysics graduate (IIT (ISM) Dhanbad) and this repository is a learning series: each part adds one idea.

**All data here are SYNTHETIC** (computed from simple forward models). No field data.

| Part | Notebook | What it does |
|---|---|---|
| 1 | `part1_brute_force_depth_scan.ipynb` | Forward model of a buried sphere; residual, misfit and RMS; a brute-force scan over depth to find the best-fitting depth; shows how a wrong density assumption biases the depth |

More parts will follow (least squares, regularised inversion).

These are guided study exercises: the notebooks were set up as exercises.

Run in Google Colab or Jupyter with NumPy and Matplotlib.
