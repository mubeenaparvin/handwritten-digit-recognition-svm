# Handwritten Digit Recognition (SVM)

Recognises handwritten digits (0-9) from 8x8 pixel images using a
Support Vector Machine (SVM) classifier.

## What this project covers
- Understanding how images are stored as numbers (a grid of pixel values)
- Displaying images with matplotlib
- Train/test split (70/30)
- Training an SVM classifier for 10-class classification
- Predicting a single image and comparing with the true label
- Comparing SVM settings: linear vs RBF kernel, `gamma` and `C`

## Tech stack
Python, pandas, NumPy, matplotlib, scikit-learn

## Dataset
1,797 images of handwritten digits. Each image is 8x8 pixels (64 columns,
`pixel_0` to `pixel_63`, values 0-16) with a `label` column holding the true
digit. Place `digits.csv` in a `data/` folder to run the notebook.

## How to run
1. Clone the repo: `git clone https://github.com/mubeenaparvin/handwritten-digit-recognition-svm.git`
2. Install dependencies: `pip install pandas numpy matplotlib scikit-learn jupyter`
3. Open `02_handwritten_digit_recognition_svm.ipynb` in Jupyter and run all cells.

## Author
Mubeena Parvin V.N.
