# Student Exam Score Prediction
## 1. Project Overview

In this project, I wanted to see if I could predict a student's exam score using data. My goal was to build a few different models, starting with a very simple one and getting more complex, to figure out which factors are most important for predicting scores.

To do this, I followed a pretty standard process:
* **Exploring the Data:** First, I just looked at the data to understand it and clean it up.
* **Building Models:** I started with a basic model and then tried a couple of more advanced ones to improve the results.
* **Evaluating Models:** I used some common metrics (like R-squared) to check how good each model was.
* **Visualizing Results:** I created graphs to help see what the data and my model's predictions looked like.

## 2. Technologies Used

* **Python 3.12.10**
* **Jupyter Notebook**
* **Pandas:** For handling all the data.
* **Matplotlib:** For making the graphs.
* **Scikit-learn:** For building the actual machine learning models.

## 3. How to Use This Project

If you want to run this project yourself, here’s how:

**Step 1: Clone the Repository**
```bash
git clone <your-github-repository-url>
cd student-score-prediction
```

***Step 2: Set Up a Virtual Environment***
* I'd recommend using a virtual environment so the libraries don't interfere with your other projects.
```bash
# Create the virtual environment
python -m venv venv

# Activate it (on Windows)
.\venv\Scripts\activate

# Activate it (on macOS/Linux)
source venv/bin/activate
```
***Step 3: Install Dependencies***
* This command will install all the libraries listed in the requirements.txt file.
```bash
pip install -r requirements.txt
```

***Step 4: Launch JupyterLab***
* This will start up the Jupyter environment in your browser.
```bash
jupyter-lab
```

***Step 5: Run the Notebook***
* In JupyterLab, just open the student-score-prediction.ipynb file and run the cells from top to bottom to see my whole process.

## 4. Project Structure
* student-score-prediction.ipynb: This is the main notebook with all my code and notes.

* StudentPerformanceFactors.csv: This is the dataset I used.

* README.md: You're reading it!
* requirements.txt: The file listing the libraries needed for the project.

* ProjectReport_Zeeshan.pdf: The project report ofcourse!