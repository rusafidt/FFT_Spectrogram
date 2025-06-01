# Course Work – Audio Signal Processing & Analysis

This project contains Python-based coursework focused on audio signal analysis and visualization.  
It includes code to process `.wav` audio files, perform transformations like Fast Fourier Transform (FFT), apply filtering techniques, and visualize waveforms using plots.  
Interactive audio playback is supported for exploring sound characteristics.

---

## 🔍 Features

- 📈 **Waveform Visualization**: Plot time-domain representations of audio signals.
- ⚙️ **FFT Analysis**: Convert signals to the frequency domain using FFT and visualize spectral content.
- 🎚️ **Filtering**: Apply signal processing filters to isolate or remove frequencies.
- 🔁 **Inverse Transforms**: Reconstruct time-domain signals from processed frequency data.
- 🔊 **Audio Playback**: Play audio within a Jupyter Notebook for inspection and comparison.

---

## 📁 Contents

- Python code cells for reading, transforming, and visualizing audio data.
- Plots: Time-domain and frequency-domain visualizations.
- WAV file handling: Read and convert audio files into arrays for analysis.
- Signal transformations: FFT, iFFT, and basic filtering using `scipy.signal`.
- Notebook export: Provided as `.html` for easy sharing or viewing outside Jupyter.

---

## 🛠️ Requirements

To run this project in a virtual environment, install the following:

```bash
pip install numpy pandas matplotlib scipy seaborn ipython
