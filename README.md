# **Speech Emotion Recognition**
Speech Emotion Recognition is a project that aims to recognize human emotions from speech signals using machine learning techniques. The project uses a dataset of speech samples labeled with emotions such as happiness, sadness, anger, and neutral to train a machine learning model to recognize emotions from speech.

# **Dependencies**
The project is implemented in Python and requires the following dependencies:

* Python 3.x
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Librosa

# **Dataset**
The dataset used for this project is the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS). It consists of 7356 files (total size: 24.8 GB). Each file contains a speech signal spoken by a professional voice actor in a particular emotion (happiness, sadness, anger, neutral, etc.).

# **Preprocessing**
The speech samples are preprocessed before being fed to the machine learning model. The preprocessing steps include:

* Resampling the speech signal to a fixed sample rate (16 kHz)
* Extracting Mel-frequency cepstral coefficients (MFCCs) from the speech signal
* Normalizing the MFCCs to zero mean and unit variance

# **Model Training**
The machine learning model used for this project is a support vector machine (SVM) with a radial basis function (RBF) kernel. The model is trained on the preprocessed speech samples using 10-fold cross-validation. The model achieves an accuracy of around 70% on the RAVDESS dataset.

# **License**
This project is licensed under the MIT License. See the LICENSE file for more information.