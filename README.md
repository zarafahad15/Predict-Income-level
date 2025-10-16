# Predict-Income-level
1. Requirements
	•	Python 3.8 or higher
	•	Streamlit
	•	pandas
	•	scikit-learn

Install required packages using:

pip install -r requirements.txt

Or individually:

pip install streamlit pandas scikit-learn


⸻

2. Project Structure

predict_income_app/
├── data/
│   └── adult.csv         # Dataset
├── app.py                # Main Streamlit app
├── requirements.txt
└── README.md

	•	Make sure the dataset adult.csv is inside the data/ folder.

⸻

3. Running the App (Windows / Mac / Linux)
	1.	Open Command Prompt or PowerShell (Windows)
Or Terminal (Mac/Linux)
	2.	Navigate to the project folder:

cd path\to\predict_income_app

	3.	Run the app using Streamlit:

streamlit run app.py

	4.	Wait a few seconds. Streamlit will open your default browser automatically at:

http://localhost:8501

	•	If it doesn’t open automatically, copy the URL from the terminal into your browser.

⸻

4. Using the App
	1.	Enter the person’s details (age, workclass, education, occupation, etc.) in the sidebar.
	2.	The predicted income (>50K or <=50K) will appear instantly.

⸻

5. Troubleshooting
	•	If you see streamlit: command not found, try:

python -m streamlit run app.py

	•	Make sure all required packages are installed:

pip install streamlit pandas scikit-learn

	•	Make sure Python is added to your system PATH.

⸻

This README gives a complete, beginner-friendly guide to running the app locally.
If you want, I can also make a “ready-to-run” Windows batch file so you can just double-click to launch the app without opening PowerShell at all.

Do you want me to do that?
