<div align="center">

# AxisDataCleaning

An offline **trajectory smoothing, resampling, and evaluation toolkit**  
**Raw teleoperation → Clean trajectories → Metrics & offline task checking**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![NumPy](https://img.shields.io/badge/NumPy-%3E%3D1.26-blueviolet)
![SciPy](https://img.shields.io/badge/SciPy-Interpolation%20%26%20Filtering-orange)
![License](https://img.shields.io/badge/License-Apache%202.0-green)

</div>

---

## Overview

`AxisDataCleaning` provides an end-to-end **offline trajectory processing pipeline** for Axis teleoperation data.

The repository includes tools to ingest JSON/CSV trajectories, smooth and resample joint data, compute before/after metrics, validate trajectories against offline task checkers, and batch-process datasets.

> The detailed CLI documentation and examples remain available in the repository history while this README is being reorganized into a clearer project guide.

## Development hygiene

Local Python environments, bytecode, test/tool caches, build artifacts, IDE metadata, and OS-generated files are ignored through the repository `.gitignore`.
