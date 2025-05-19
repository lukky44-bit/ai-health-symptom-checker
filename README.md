# ai-health-symptom-checker
AI-Powered Symptom Checker with Emergency Alert A machine learning-based health assistant that predicts diseases from user symptoms, displays their description and precautions, and triggers an emergency alert for severe cases using a Tkinter GUI.
## Project Structure
ai-health-symptom-checker/
│
├── models/
│ ├── vectorizer.pkl
│ ├── label_encoder.pkl
│ ├── symptom_diagnosis_model_keras.h5
│
├── data/
│ ├── description.csv
│ ├── precautions.csv
│ ├── severity.csv
│
├── ui.py
├── model_training.ipynb
├── README.md
├── requirements.txt

## Features

- Predicts diseases based on symptoms input by the user.
- Displays disease description and necessary precautions.
- Checks symptom severity and alerts if emergency help (108) is recommended.
- Uses a Keras deep learning model trained on symptom data.

## Installation

1. Clone the repository:

## Features

- Predicts diseases based on symptoms input by the user.
- Displays disease description and necessary precautions.
- Checks symptom severity and alerts if emergency help (108) is recommended.
- Uses a Keras deep learning model trained on symptom data.

## Installation

1. Clone the repository:

## Features

- Predicts diseases based on symptoms input by the user.
- Displays disease description and necessary precautions.
- Checks symptom severity and alerts if emergency help (108) is recommended.
- Uses a Keras deep learning model trained on symptom data.

## Installation

1. Clone the repository: git clone https://github.com/lukky44-bit/ai-health-symptom-checker.git
cd ai-health-symptom-checker
2. Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate # On Windows use: venv\Scripts\activate
3. Install dependencies:
pip install -r requirements.txt

## Usage

Run the UI application:
python ui.py

Enter symptoms separated by commas and click "Predict Disease" to get the diagnosis, description, and precautions. If symptoms indicate high severity, an emergency button will appear.

## Dataset

- `description.csv`: Contains disease descriptions.
- `precautions.csv`: Contains precautions for each disease.
- `severity.csv`: Symptom severity scores used to determine emergency alerts.

## License

This project is licensed under the MIT License.

---

Feel free to contribute or raise issues!


