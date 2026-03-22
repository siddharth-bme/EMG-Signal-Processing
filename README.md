# EMG-Signal-Processing
EMG gesture classification for myoelectric prosthetics control — NinaPro DB1 dataset
# EMG Signal Processing for Neuroprosthetics

Surface EMG gesture classification using the NinaPro DB1 dataset.
Built as part of MSc Biomedical Engineering research at the University of Glasgow.

## What this project does
- Loads and visualises raw surface EMG signals from 10 forearm channels
- Applies 20-450 Hz bandpass filtering to remove noise
- Extracts time-domain features (RMS, MAV, Zero Crossings, Waveform Length)
- Classifies 6 hand gestures using Support Vector Machine (SVM)
- Achieves ~XX% accuracy on held-out test data

## Dataset
NinaPro Database 1 — publicly available at ninapro.hevs.ch
Cipriani et al., 2011 — used in 500+ published papers worldwide

## Technologies
Python · NumPy · SciPy · Scikit-learn · Matplotlib

## Relevance
This work is directly related to myoelectric prosthetics control —
decoding motor intent from muscle signals to drive assistive devices.
It forms the foundation of my MSc dissertation on EMG-controlled FES.

## Author
[Your Name] — MSc Biomedical Engineering, University of Glasgow
[Your LinkedIn URL]
