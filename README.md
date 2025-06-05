# Speech Emotion Recognition in White Noise

This project investigates the impact of **white noise and signal-to-noise ratio (SNR)** on **Speech Emotion Recognition (SER)** — a key challenge for deploying SER systems in real-world, acoustically adverse environments (e.g., public transport, hearing aids, assistive tech).

> This research is part of my MSc dissertation in Language Sciences: Technology of Language and Speech @ UCL.

---

## Project Objective

- Analyse how different **SNR levels** affect the performance of emotion classification models  
- Build a noise-aware SER benchmark using the **RAVDESS** dataset  
- Apply **signal processing techniques** to simulate real-world degradation  
- Train and evaluate models (traditional and deep learning) under varying noise conditions  
- Establish practical **thresholds and recommendations** for SER robustness in noisy environments

---

## Core Features

- Noise injection pipeline for white noise with adjustable SNR  
- Extraction of acoustic features (e.g. **MFCCs**, pitch, energy) using **Librosa**  
- Training of **XGBoost classifiers** and deep models (planned)  
- Benchmark generation and performance comparison across SNR levels  
- Visualisation of performance degradation using **Seaborn** & **Matplotlib**

---

## Technologies Used

| Tool/Library         | Purpose                                 |
|----------------------|------------------------------------------|
| Python               | Core language                           |
| Librosa              | Audio processing and feature extraction |
| NumPy, Pandas        | Data manipulation                       |
| Scikit-learn, XGBoost| ML training and evaluation              |
| Seaborn, Matplotlib  | Data visualisation                      |
| Google Colab         | Cloud-based experimentation             |

---

## Exploratory Data Analysis (EDA)

Initial analysis of the **RAVDESS** dataset (Livingstone & Russo, 2018) was conducted in Google Colab.

EDA Notebook: *Coming soon*

---

## Project Structure

```
ser_in_noise/
├── audio/ # Raw and modified audio files
├── features/ # Extracted MFCCs and acoustic features
├── models/ # Saved model weights (future)
├── results/ # Evaluation results and benchmark files
├── notebooks/ # Colab notebooks for EDA and experimentation
├── src/ # (Planned) Modular scripts for training pipeline
├── LICENSE # MIT License
└── README.md # This file
```

---

## How to Run

Code and pipeline modularisation is in progress. Core functions are currently in **Google Colab** notebooks.

Check back soon for runnable Python scripts and setup instructions.

---

## Contributing

This project is currently a research submission and not open to external contributions.  
You're welcome to follow the repository and revisit once the final version is published.

---

## License

This project is licensed under the **MIT License** — see the `LICENSE` file for full terms.

---

## Author

**Tatiana Limonova**  
*MSc Language Sciences (Technology of Language and Speech) – UCL*  
[GitHub](https://github.com/kanincityy) • [LinkedIn](https://linkedin.com/in/tatianalimonova)

---

Thanks for your interest & stay tuned for benchmarks! ✨🐇
