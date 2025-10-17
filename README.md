# Session 1 — Big Data and Business Intelligence

This repository contains the materials for **Session X** of *Course Y*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---

## 📑 Session Outline
### Introduction to Big Data & Business Intelligence
---

### Learning Objectives
By the end of this session, you will be able to:
- Explain what *data*, *Big Data*, and *Business Intelligence (BI)* mean.  
- Distinguish between structured, semi-structured, and unstructured data.  
- Describe the data lifecycle and understand where data warehouses and lakes fit in.  
- Understand the role of databases (SQL vs NoSQL).  
- Recognize how BI transforms data into decisions using KPIs and dashboards.  
- Set up your own GitHub workspace for this course.

---

### Key Takeaways
- Data is the foundation of modern decision-making.  
- BI bridges the gap between raw data and actionable insight.  
- Understanding the data lifecycle is key before jumping into analysis.  
- Collaboration and version control with GitHub are essential professional skills.


---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```
