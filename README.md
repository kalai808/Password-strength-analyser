# Password Strength Analyzer & Security Checker

## Project Overview
A beginner-friendly cybersecurity project developed for the IBM SkillsBuild Cyber Security BootCamp 2026. The project evaluates password strength using multiple security checks.

## Objectives
- Identify weak passwords.
- Check password complexity.
- Provide a simple security score.
- Give recommendations for stronger passwords.
- Demonstrate Python programming in a cybersecurity use case.

## Technologies Used
- Python 3
- Jupyter Notebook
- Regular Expressions (`re`)
- `getpass`

## Dataset
No external dataset is required. The project uses a small built-in educational list of commonly used weak passwords. Therefore, there is no external dataset download link.

## Features
- Length validation
- Uppercase/lowercase detection
- Number detection
- Special-character detection
- Common-password detection
- Score out of 7
- Weak/Medium/Strong/Very Strong classification
- Security recommendations

## Project Files
```text
KalaiyarasanV_PasswordStrengthAnalyzer.ipynb
requirements.txt
KalaiyarasanV_ProjectReport.docx
README.md
```

## Requirements
Python 3.x and Jupyter Notebook.

## Installation
No third-party packages are required.

## How to Run
1. Install Python 3.
2. Open the `.ipynb` file in Jupyter Notebook, JupyterLab, or Google Colab.
3. Run the code cell.
4. Enter a test password when prompted.
5. Review the security score and recommendations.

## Example
For an educational test password such as `Test@12345Secure`, the analyzer checks length, character types, and common-password status and produces a strength classification.

## Security & Privacy
The program does not save or transmit the password. Do not enter real account passwords into demonstration environments.

## Future Enhancements
- Password entropy estimation
- Breached-password checking through a privacy-preserving API
- GUI/web interface
- Password generator
- Strength visualization

## Author
KalaiyarasanV
