# fastrerandomize

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

An R package for hardware-accelerated rerandomization and exact randomization testing in experimental design.

## Features

- 🚀 GPU/CPU-accelerated randomization generation via JAX
- 🔢 Supports both exact enumeration and Monte Carlo sampling
- 📉 Built-in balance metrics (Hotelling's T²) and custom threshold functions
- 📈 Randomization-based inference with fiducial intervals
- 💾 Memory-efficient batched processing for large experiments

## Installation

```r
# Install from GitHub
devtools::install_github("cjerzak/fastrerandomize-software/fastrerandomize")

# Build Python backend (requires conda)
library(fastrerandomize)
build_backend(conda_env = "fastrerandomize")
