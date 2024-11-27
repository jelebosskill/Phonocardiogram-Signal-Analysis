# Phonocardiogram Signal Analysis

## Project Overview

This project provides a detailed analysis of audio WAV signals to identify and analyze heart cycle peaks. The goal is to develop Python tools that extract valuable information from audio data, focusing on heart cycle characteristics. The notebook outlines steps from time-domain signal representation to frequency analysis, filtering, and peak detection. Additionally, it compares cardiac energy across multiple recordings for a comprehensive assessment.

## Table of Contents

1. **Signal Visualization**
   - Load and display time-domain WAV audio signals.
2. **Frequency Representation**
   - Calculate frequency spectrum and spectrogram using Fourier Transform.
3. **Filtering and Noise Reduction**
   - Normalize audio signals and apply Butterworth band-pass filtering.
4. **Epoch Energy Analysis**
   - Analyze energy epochs of band-pass filtered signals.
5. **Filtering Operations**
   - Perform time-axis corrections and detect signal peaks.
6. **Peak Distance Calculation**
   - Calculate temporal distances between detected peaks.
7. **Identification of B1 and B2 Peaks**
   - Identify B1 and B2 peaks from detected signal peaks.
8. **Margin-Based B1 and B2 Detection**
   - Robustly calculate B1 and B2 points with error margins.
9. **Mean-Square Values for Cardiac Phases**
   - Compute mean-square values for cardiac phases using B1 and B2 points.
10. **Energy Analysis Across Multiple Records**
    - Repeat all steps across all signals in the Records directory, analyzing and comparing results.

## Libraries Used

- **NumPy**: Numerical computations and array manipulations.
- **SciPy**: Signal processing, spectrograms, filters, and peak detection.
- **Matplotlib**: Data and signal visualization.
- **wave/scipy.io.wavfile**: Audio file reading and writing.
- **os**: File and system operations.
