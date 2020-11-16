# realtime

Real-time data analysis project for CATNIP lab

## Basic prototype

This directory contains code for a simple version of the real-time filtering system. The directory layout is as follows:

- `data`: Data used to test prototype. Contains two subdirectories:
    - `raw`: Raw Steinmetz data downloaded from server 
    - `processed`: Data derived from Steinmetz data
- `scripts`: Utility scripts for experiment
    - `fetch_steinmetz_data.py`: Fetch Steinmetz data from server
    - `create_test_signal.py`: Create signal to test prototype on
- `notebooks`: Jupyter notebooks used to analyze experiment results
    - `examine_results.ipynb`: Notebook for plotting latency test results
- `julia`: Julia implementation of real-time filtering prototype
- `python`: Python implementation of real-time filtering prototype
- `rust`: Rust implementation of real-time filtering prototype
