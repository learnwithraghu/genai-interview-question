# Data Detective: Cruise Ship Investigation 🚢

A Python data analysis interview challenge that simulates investigating a theft on a luxury cruise ship using passenger data, card access logs, and dining records.

## 🎯 Overview

This repository contains an interactive data analysis challenge designed to test candidates' ability to:
- Work with multiple data sources (CSV, JSON)
- Clean and process temporal data
- Perform anomaly detection
- Cross-reference and analyze suspicious patterns
- Draw conclusions from data analysis

## 📁 Repository Structure
```
genai-interview-question/
├── generate_data/          # Data generation scripts
├── solutions/             # Reference solutions (private)
├── hint_doc.py           # Progressive hints for candidates
├── InterviewQuestion.md  # Main challenge document
└── README.md            # This file
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- pandas
- numpy
- json

### Setup Options

1. **Local Setup**
```bash
# Clone the repository
git clone https://github.com/yourusername/cruise-ship-investigation.git

# Install required packages
pip install pandas numpy
```

2. **Google Colab**
- Upload the provided data files to your Colab workspace
- Import required packages using `!pip install` if needed

3. **Jupyter Notebook**
```bash
# Install Jupyter if you haven't already
pip install jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## 📝 Challenge Structure

The challenge is divided into 5 progressive tasks:
1. Data Loading & Initial Inspection
2. Timeline Establishment
3. Anomaly Detection
4. Location Analysis 
5. Final Suspect Analysis

Each task builds upon the previous ones, gradually constructing the investigation.

## 💡 Getting Help

If you get stuck:
1. Check `hint_doc.py` for progressive hints
2. Each hint provides incremental guidance without giving away the solution
3. Make sure to attempt each task before looking at hints

## 🌟 Best Practices

- Document your analysis steps
- Include explanations for your findings
- Print intermediate results to verify your analysis
- Consider edge cases in your investigation
- Think about real-world implications of the patterns you find

## 📊 Sample Data Format

The repository includes three data files:
- `passenger_manifest.csv`: Passenger details
- `card_access_logs.json`: Key card access records
- `dining_transactions.csv`: Dining hall purchase records

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 🎓 Learning Objectives

This challenge tests candidates' abilities in:
- Data wrangling with pandas
- Time series analysis
- Pattern detection
- Logical reasoning
- Data visualization (optional)
- Investigative thinking

Good luck with your investigation! 🕵️‍♂️✨