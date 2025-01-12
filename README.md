# translation-project
his repository contains a Python-based GUI application for translating English sentences to Spanish using a Transformer-based model. The project leverages modern NLP techniques and provides a user-friendly interface for translation and model interaction.

Features:
Intuitive GUI: Built with tkinter, the app allows users to interact easily by selecting sentences for translation.
Dataset Support: Load English-Spanish sentence datasets from CSV files to train the model or create mappings.
Transformer Model: A Transformer-based encoder-decoder architecture powers the translations, using TensorFlow/Keras.
Translation Mappings: Automatically maps English sentences to their Spanish counterparts for efficient lookup.
Model Persistence: Save and load mappings and trained models using pickle and TensorFlow functionalities.
Customizable Translations: Translate sentences from a predefined dataset or a trained model with real-time results.
Key Technologies:
GUI: tkinter and ttk for creating interactive and dynamic interfaces.
Data Handling: pandas and numpy for dataset loading and numerical operations.
Modeling: TensorFlow/Keras for building and training the Transformer model.
Pickle: Save and load mappings and Python objects efficiently.
How to Use:
Load Dataset: Use the GUI to load a CSV file containing English and Spanish sentences.
Train Model: Automatically train a Transformer-based model on the loaded dataset.
Translate Sentences: Select an English sentence from the dropdown and view its Spanish translation.
Save/Load Mappings and Models:
Save mappings for quick translations without retraining.
Load pre-trained models for immediate use.
Setup:
Clone the repository:
bash
Copy code
git clone <repository_url>
cd translator_app
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the application:
bash
Copy code
python app.py
Folder Structure:
app.py: Main GUI and logic file.
mappings.pkl: Stores mappings between English and Spanish sentences.
translator_model.h5: Trained TensorFlow model for translations.
data/: Folder to store CSV datasets.
Dependencies:
tkinter, pandas, numpy, tensorflow, pickle
