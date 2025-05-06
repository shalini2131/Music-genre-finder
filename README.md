# Music-genre-finder
# 🎵 Music Genre Classification 🎵

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shalini2131/Music-genre-finder/blob/main/music_genre_classification.ipynb)

This project demonstrates how to classify music genres using neural networks. It explores the fundamentals of **Artificial Neural Networks (ANNs)** and **Convolutional Neural Networks (CNNs)** by training models on audio features extracted from music files.

---

## 📁 Project Structure

The notebook is organized into three main parts:

1. **ANN-based Classification**  
   A basic feedforward network using Keras.

2. **Overfitting Solutions in ANN**  
   Techniques like dropout and early stopping are applied to improve generalization.

3. **CNN-based Classification**  
   A convolutional model to capture spatial features from spectrograms.

---

## 🎧 Dataset 🎵

- Used `librosa` for feature extraction.
- One file was skipped due to size limitations in Colab.
- The dataset includes the following genres as labels:
  - `0`: Disco
  - `1`: Metal
  - `2`: Reggae
  - `3`: Blues
  - `4`: Rock
  - `5`: Classical
  - `6`: Jazz
  - `7`: Hiphop
  - `8`: Country
  - `9`: Pop

---

##  Technologies Used

- Python
- TensorFlow / Keras
- Librosa
- NumPy / Pandas
- Matplotlib

---

##  Getting Started

You can open the notebook directly in Google Colab using the badge above.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Music-genre-finder.git
   ```
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
3. Open the notebook in Jupyter or Google Colab.
