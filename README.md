# Climate Challenge – Week 0

## Project Overview

This repository contains the Week 0 challenge for the 10x Academy Artificial Intelligence Mastery program. The objective is to explore, clean, and analyze historical climate data across selected African countries to extract meaningful insights that can support climate policy discussions.

The project follows a structured data science workflow including environment setup, data preprocessing, exploratory data analysis (EDA), and cross-country comparison.

---

## Objectives

- Set up a reproducible Python development environment
- Practice Git and GitHub workflows (branching, commits, pull requests)
- Perform data cleaning and exploratory data analysis
- Generate insights on climate trends across multiple African countries
- Prepare results suitable for policy-level interpretation

---

## Project Structure

```
climate-challenge-week0/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── notebooks/
├── src/
├── tests/
├── scripts/
│
├── .gitignore
├── requirements.txt
├── README.md
```

---

## Environment Setup

### 1. Clone the repository

```bash
git clone https://github.com/tsi122124/climate-challenge-week0.git
cd climate-challenge-week0
```

---

### 2. Create virtual environment

```bash
python -m venv venv
```

---

### 3. Activate virtual environment

Windows (Git Bash):

```bash
source venv/Scripts/activate
```

Windows (CMD):

```bash
venv\Scripts\activate
```

Windows (PowerShell):

```powershell
venv\Scripts\Activate.ps1
```

macOS / Linux:

```bash
source venv/bin/activate
```

---

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

---

## CI/CD Integration

This project uses GitHub Actions for continuous integration.

On every push to the main branch:

- Dependencies are installed automatically
- Environment setup is validated

## Notes

- Data files are ignored
- CI runs on push to main
