# Disease-Prediction-Model

This is a Disease Prediction Model that uses machine learning models to predict diseases based on input symptoms. It provides a user-friendly graphical interface where users can input symptoms, and the system predicts the likely disease using trained models.

## Features

- Predict diseases using three machine learning models: Decision Tree, Random Forest, and Naive Bayes.
- User-friendly graphical interface built with Tkinter.
- Trained models based on a dataset of symptoms and corresponding diseases.
- Display of predicted diseases for each model.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python (version 3.x)
- Required Python libraries: Tkinter, PIL, numpy, pandas, scikit-learn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rishii100/Disease-Prediction-Model.git
   ```

2. Change to the project directory:

   ```bash
   cd Disease-Prediction-Model
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

Run the main script to launch the application:

```bash
python prediction.py
```

Follow the on-screen instructions to input symptoms and use the prediction system.

## Project Structure

- `main.py`: Main script for running the GUI application.
- `Training.csv`: CSV file containing training data for machine learning models.
- `Testing.csv`: CSV file containing testing data for evaluating model accuracy.
- `bg.jpg`: Background image used in the GUI.

## License

This project is licensed under the [Your License] - see the [LICENSE.md](LICENSE.md) file for details.
