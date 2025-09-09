#  Student Performance & Job Placement Prediction  

This project predicts **student performance (CGPA)** and whether a student will **get a job placement** based on multiple features such as study hours, attendance, internships, projects, technical skills, soft skills, and extracurricular activities.  

---

##  Features  
- **Regression Model** → Predicts student **CGPA**.  
- **Classification Model** → Predicts **Job Placement (Yes/No)**.  
- **Data Preprocessing** → Label Encoding & One-Hot Encoding.  
- **Evaluation Metrics**:  
  - For Job Placement → Accuracy, Precision, Recall, F1 Score, Confusion Matrix.  
  - For CGPA → Mean Absolute Error (MAE), R² Score.  
- **Visualization** → Shows relationships like Attendance vs. CGPA.  

---

##  Tech Stack  
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Scikit-learn** – Machine Learning models (Decision Tree, Random Forest, KNN)  
- **Matplotlib** – Visualization  

---

##  Dataset  
The dataset contains the following features:  

| Column              | Description |
|----------------------|-------------|
| Age                 | Age of student |
| StudyHoursPerWeek   | Average weekly study hours |
| AttendanceRate      | Attendance percentage |
| Internships         | Number of internships done |
| ProjectsDone        | Number of academic projects completed |
| TechnicalSkills     | Count of technical skills |
| SoftSkills          | Level (1 = Beginner, 2 = Intermediate, 3 = Advanced) |
| Extracurricular     | Type of extracurricular activity |
| CGPA                | Cumulative Grade Point Average |
| JobPlacement        | Placement status (Yes/No) |

---

##  How to Run  
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/student-performance-prediction.git
   cd student-performance-prediction
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script  
   ```bash
   python student_model.py
   ```

---

##  Results  
- **Job Placement Model** → Achieved **100% accuracy** on sample dataset (Decision Tree).  
- **CGPA Model** → Random Forest gave an **R² Score of 0.73**, showing good performance.  

---

##  Future Improvements  
- Add **Flask API** for backend integration.  
- Build a **ReactJS UI** for interactive predictions.  
- Train with a **larger real-world dataset** for better generalization.  

---

## 👨‍💻 Author  
**Sandip Chakraborty**  
- 💻 BCA Student | Aspiring Software Developer & Data Scientist  
- 🌐  |  
