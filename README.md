# log-file-analysis
## Web Log Analysis and Suspicious Activity Detection

## Overview
This project is designed to analyze web log files, extract meaningful insights, and detect suspicious activities such as potential security risks. It processes log data from a sample log file (`sample.log`) to identify patterns, including IP request counts, most accessed endpoints, and suspicious activity based on failed login attempts. 

The goal is to provide a clear, comprehensive analysis of web traffic, helping web administrators identify potential threats and optimize web traffic management.

## Features
- **IP Request Count**: Tracks the number of requests made by each IP address.
- **Most Accessed Endpoint**: Identifies the most frequently accessed endpoint (URL).
- **Suspicious Activity Detection**: Flags IP addresses with multiple failed login attempts, which may indicate suspicious behavior.

## Technologies Used
- **Python**: The primary language for data analysis and processing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations.
- **Seaborn**: For enhancing Matplotlib plots with better aesthetics and statistical plots.

## How to Run the Project

### Step 1: Clone the Repository
Clone this repository to your local machine using Git.

```bash
git clone https://github.com/your-username/web-log-monitoring.git

### Step 2: Virtual Environemnt & Installing Dependencies
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

pip install -r requirements.txt

### Step 3: Run the script
python log_analysis.py

