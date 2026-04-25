# Aroldis Chapman Pitch Analysis

## Overview:
This project seeks to analyze Aroldis Chapman's pitch mix, spin rate, and velocity analytics to see if his age has truly affected his performance.

## Key Findings:
- I found that his velocity with his fastball and sinker has maintained steadily between 2020 and 2024.
- He has significantly mixed up his pitch usage, with 73.5% of his pitches being fastballs in 2020 to just 33% by 2024. He has incorporated a lot more sinkers into his arsenal, from 5.6% to 27.7% between 2020 & 2024.
- His Splitter spin rate was heavily affected during the mid-season 2021 crackdown of illegal foreign substance usage, dropping nearly 550 RPM.

My findings conclude that his performance has not declined as a result of his age between 2020 and 2024.

## Technologies Used:
Python libraries - pandas, matplotlib, pybaseball
Sources - Statcast using pybaseball

## How to Run:
Clone the repo:
```bash
git clone https://github.com/mrbuddyoldpal/pitcher-profile.git
```

Make a venv environment inside the cloned folder:
```bash
python3 -m venv venv
source venv/bin/activate
```

Install the libraries using the requirements.txt file:
```bash
pip install -r requirements.txt
```

Run Jupyter:
```bash
jupyter notebook
```

LASTLY:
Open the chapman_profile notebook from the notebooks/ folder and run all cells.
