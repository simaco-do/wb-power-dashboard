# WB Power Services - Equipment Failure Prediction Dashboard

[![Live Dashboard](https://img.shields.io/badge/Live-Dashboard-blue?style=for-the-badge)](https://YOUR-USERNAME.github.io/wb-power-dashboard/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/YOUR-USERNAME/wb-power-dashboard)

> **MSc Dissertation Project**  
> Developing an Advanced Machine Learning Algorithm for Equipment Failure Prediction:  
> A Case Study of WB Power Services Ltd Using Protean System Data

---

## 🎯 Live Dashboard

**[Click here to view the live interactive dashboard →](https://YOUR-USERNAME.github.io/wb-power-dashboard/)**

---

## 📊 Project Overview

This interactive web-based dashboard visualizes equipment failure predictions using machine learning algorithms trained on 10 years of operational data from WB Power Services Ltd's Protean database system.

### Key Features

- ⚡ **Real-time Risk Prediction**: Predict equipment failure risk with 96.52% F1 score
- 📈 **Interactive Visualizations**: Dynamic charts showing model performance and risk patterns
- 🔍 **HDG Equipment Analysis**: Detailed analysis of Hire Desk Group (HDG) equipment showing 12.9× higher failure risk
- 📉 **Bathtub Curve Analysis**: Equipment age-based failure patterns
- 🎯 **Feature Importance**: Top predictive features from the LightGBM model
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices

---

## 📚 Academic Information

**Student:** Simon Akporowhe  
**Student ID:** 24044525  
**Institution:** University of Bradford  
**Program:** MSc in Applied AI and Data Analytics  
**Year:** 2024/2025

**Dissertation Title:**  
*Developing an Advanced Machine Learning Algorithm for Equipment Failure Prediction: A Case Study of WB Power Services Ltd Using Protean System Data*

---

## 🔬 Research Highlights

### Dataset
- **Total Records:** 3,970,500 rows from 17 source tables
- **Final Dataset:** 20,233 equipment records × 92 features
- **Time Span:** 2015-2025 (10 years)
- **Data Source:** WB Power Services' Protean database system

### Machine Learning Model
- **Algorithm:** LightGBM (Light Gradient Boosting Machine)
- **Classification:** Binary (0 = Not at Risk, 1 = At Risk)
- **F1 Score:** 96.52%
- **ROC AUC:** 98.71%
- **Accuracy:** 96.41%
- **Overfitting Gap:** 1.91% (excellent generalization)

### Key Findings
1. **HDG Equipment Risk:** 74.95% failure rate vs 5.80% for Non-HDG (12.9× higher)
2. **Top Predictive Features:** Status codes, equipment age, make/model ID
3. **Age-Based Patterns:** Deviation from classical bathtub curve observed
4. **At-Risk Equipment:** 1,648 out of 20,233 (8.14%)

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3 (Custom Dark Theme)
- JavaScript (ES6+)

### Data Visualization
- [Chart.js](https://www.chartjs.org/) - Interactive charts
- Custom CSS Grid layouts
- Responsive design principles

### Machine Learning
- **Python:** Data preprocessing and model training
- **LightGBM:** Primary ML algorithm
- **scikit-learn:** Model evaluation and preprocessing
- **pandas:** Data manipulation
- **NumPy:** Numerical operations

### Deployment
- GitHub Pages (Static hosting)
- Git version control

---

## 📂 Repository Structure

```
wb-power-dashboard/
│
├── index.html              # Main dashboard file
├── README.md              # This file
└── assets/                # (Optional) Additional resources
    ├── images/           # Screenshots, diagrams
    └── data/             # Sample data files
```

---

## 🖼️ Dashboard Screenshots

### Overview Tab
![Dashboard Overview](https://via.placeholder.com/800x400?text=Dashboard+Overview)
*Binary classification distribution and key statistics*

### Model Performance
![Model Performance](https://via.placeholder.com/800x400?text=Model+Performance)
*F1 scores and ROC AUC comparison across 8 ML algorithms*

### HDG Analysis
![HDG Analysis](https://via.placeholder.com/800x400?text=HDG+Equipment+Analysis)
*12.9× failure rate differential between HDG and Non-HDG equipment*

*(Replace placeholder images with actual screenshots of your dashboard)*

---

## 🚀 How to Use

### View Online
Simply visit: **[https://YOUR-USERNAME.github.io/wb-power-dashboard/](https://YOUR-USERNAME.github.io/wb-power-dashboard/)**

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/wb-power-dashboard.git
   ```
2. Open `index.html` in your web browser
3. No build process or dependencies required!

---

## 📊 Dashboard Sections

### 1. Overview
- Final dataset summary (equipment_df: 20,233 × 92)
- Three merged datasets visualization
- Binary risk distribution
- Model performance comparison
- HDG vs Non-HDG analysis

### 2. Data Sources
- 17 source tables from Protean system
- Data integration pipeline
- Source table statistics
- Memory usage analysis

### 3. Model Performance
- 8 ML algorithms compared
- F1 Score, Accuracy, ROC AUC metrics
- Overfitting analysis
- LightGBM detailed performance

### 4. Feature Analysis
- Feature importance comparison (4 models)
- Top 13 predictive features
- Dataset contribution breakdown
- Equipment vs Job vs Service features

### 5. Risk Patterns
- Equipment age bathtub curve
- Status code failure analysis
- Age-based risk multipliers

### 6. Risk Predictor
- Interactive equipment risk calculator
- Real-time predictions
- Binary classification output (At Risk / Not at Risk)

---

## 🎓 Research Contributions

### Methodological
- Effective handling of severe class imbalance (11.3:1 ratio)
- Feature engineering from multi-table operational databases
- Binary classification framework for actionable maintenance decisions

### Empirical
- Equipment age-based risk patterns deviate from classical bathtub curves
- HDG hire equipment exhibits 12.9× failure differential
- Operational status codes provide dominant predictive signal

### Practical
- Deployment-ready predictive maintenance system
- 96.52% F1 score enables proactive maintenance scheduling
- HDG equipment challenge offers highest-leverage intervention opportunity

---

## 📝 Citations

If you use this dashboard or findings in your research, please cite:

```bibtex
@mastersthesis{akporowhe2025equipment,
  title={Developing an Advanced Machine Learning Algorithm for Equipment Failure Prediction: 
         A Case Study of WB Power Services Ltd Using Protean System Data},
  author={Akporowhe, Simon},
  year={2025},
  school={University of Bradford},
  type={MSc Dissertation},
  note={Interactive dashboard available at: https://YOUR-USERNAME.github.io/wb-power-dashboard/}
}
```

---

## 🔗 Links

- **Live Dashboard:** [https://YOUR-USERNAME.github.io/wb-power-dashboard/](https://YOUR-USERNAME.github.io/wb-power-dashboard/)
- **GitHub Repository:** [https://github.com/YOUR-USERNAME/wb-power-dashboard](https://github.com/YOUR-USERNAME/wb-power-dashboard)
- **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com/in/YOUR-PROFILE)
- **University:** [University of Bradford](https://www.bradford.ac.uk/)

---

## 📧 Contact

**Simon Akporowhe**  
MSc Applied AI and Data Analytics  
University of Bradford  
Student ID: 24044525

For questions about this research or dashboard:
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your Profile](https://www.linkedin.com/in/YOUR-PROFILE)
- 🐙 GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)

---

## 📄 License

This project is part of an MSc dissertation at the University of Bradford.  
The dashboard is publicly accessible for educational and research purposes.

**WB Power Services Ltd** data used with permission for academic research.

---

## 🙏 Acknowledgments

- **WB Power Services Ltd** for providing access to the Protean database system
- **University of Bradford** for academic supervision and support
- **Dissertation Supervisor:** [Supervisor Name] for guidance throughout the research
- **Chart.js** for the excellent data visualization library

---

## 📊 Dashboard Stats

![Visitors](https://img.shields.io/badge/Visitors-Track%20with%20Analytics-blue)
![Data Points](https://img.shields.io/badge/Data%20Points-3.97M-green)
![Accuracy](https://img.shields.io/badge/Accuracy-96.41%25-success)
![F1 Score](https://img.shields.io/badge/F1%20Score-96.52%25-success)

---

<div align="center">

**Made with ❤️ for advancing predictive maintenance in critical power services**

[⬆ Back to Top](#wb-power-services---equipment-failure-prediction-dashboard)

</div>
