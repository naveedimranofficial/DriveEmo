# DriveEmo-FL-SignalPipeline

Jupyter/Anaconda implementation of the mmWave radar signal-processing pipeline used in **DriveEmo-FL**, including **micro-Doppler spectrogram extraction** and **VTP feature extraction** (agility, peak velocity, total energy). The outputs are formatted for downstream learning (e.g., EmoNet dual-stream fusion).

---

## Features
- Static clutter removal (mean subtraction + high-pass filtering)
- Adaptive background suppression (exponential moving average)
- Windowing (Hanning/Hann)
- Range FFT (1D FFT) for range profiling
- Range–Doppler processing + **2D-CFAR**
- **STFT-based micro-Doppler spectrogram** generation (e.g., 128×128)
- **VTP feature extraction**: agility, peak velocity, total energy
- Export utilities (PNG/NumPy/CSV) for training and evaluation

---

## Repository Structure
