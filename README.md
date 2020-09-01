# Voila-Jones
ECEN 649 Course Project

Dependencies:
- `Python 3.6.7`
- `numpy 1.17.3`
- `pandas 0.25.3`
- `matplotlib 3.1.2`
- `imutils 0.5.3`
- `cv2 4.1.1`

Prefer direct installation of above packages but if necessary, use `req.txt` to recreate the conda environment:
`conda create --name <env> --file req.txt`

Please first run `Combine_Features.ipynb`. It will create 2 .npy files containing features: one for faces and another for non-faces.

Then run `Robust_features_Adaboost.ipynb` (for part II in report) or `Adaboost.ipynb`  (for part III).

Read Report here:
https://htmlpreview.github.io/?https://github.com/rkapr/Voila-Jones/blob/master/Untitled.html
