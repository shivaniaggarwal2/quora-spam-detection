# Quora Spam Detection Project

This project builds a spam classifier for Quora questions using a Convolutional Neural Network (CNN) and pre-trained GloVe word embeddings.

## 📂 Files Included
- `quora_spam_detection.ipynb`: Main code notebook
- `requirements.txt`: Python libraries used
- (Optional) GloVe file: `glove.6B.100d.txt` (User needs to download)

## 📌 How to Run
1. Download GloVe from [GloVe site](https://nlp.stanford.edu/projects/glove/)
2. Place `glove.6B.100d.txt` in your working directory
3. Open `quora_spam_detection.ipynb` and run all cells

## 📊 Model
- Uses CNN + GloVe (100D) embeddings
- Trained on 1.3M Quora samples
- Achieved ~95% accuracy

## 📦 Requirements
See `requirements.txt` for full list.

## 📥 Output
Generates prediction CSV file for new questions.

## 💾 Trained Model Download
The trained model file (`quora_spam_model.h5`) is too large for GitHub, so you can download it from this link:

👉 [Download Trained Model (.h5)](https://drive.google.com/file/d/1UYnOBatfTXty5cHNykclz-QoBOIQe4a8/view?usp=sharing)

## 🔗 Additional Downloads

- 📄 Predicted Results CSV: [Download CSV](https://drive.google.com/file/d/1F_rPYml8vZrba76FrYqGrJQ04bHJBpoN/view?usp=sharing)
- 🧠 Tokenizer File: [Download tokenizer.pkl](https://drive.google.com/file/d/18zCogeO87vYP1MW2sUtbnxGY8GrRjSHX/view?usp=sharing)