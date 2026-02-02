# audio-denoising-fourier
Audio signal denoising using Fourier analysis and spectral filtering, implemented in Python.

# Audio Denoising Using Fourier Analysis

This repository presents a Python implementation of **audio signal denoising** based on
**Fourier analysis and spectral filtering**.

The project focuses on restoring clean audio signals from noisy observations using
the **Discrete Fourier Transform (DFT)** and its fast implementation (**FFT**).

---

## 📌 Project Overview

In many real-world applications, audio signals are corrupted by additive noise during
acquisition or transmission.  
We consider the classical model:

\[
y = u + \beta
\]

where:
- \( u \) is the original clean signal,
- \( \beta \) is an additive noise component,
- \( y \) is the observed noisy signal.

The objective is to estimate \( u \) from \( y \) by analyzing the signal in the
**frequency domain**.

---

## 🧠 Methodology

The denoising approach relies on:
- Discrete Fourier Transform (DFT)
- Fast Fourier Transform (FFT / IFFT)
- Spectral analysis of audio signals
- Frequency-domain filtering

The method exploits the fact that useful audio information and noise often occupy
different frequency ranges.

---

## 🛠️ Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- WAV audio processing

---

## 📂 Repository Structure
