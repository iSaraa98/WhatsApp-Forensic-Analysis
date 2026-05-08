# WhatssApp iOS Forensic Analysis

## Overview
This project presents a forensic framework for extracting and reconstructing WhatsApp artifacts from encrypted iOS backups. The framework focuses on converting raw forensic data into structured and readable communication records for digital forensic investigations.

## Objectives
- Extract WhatsApp artifacts from encrypted iOS backups
- Convert Apple timestamps into readable timestamps
- Organize message records chronologically
- Improve forensic data interpretation

## Technologies Used
- iBackup Viewer
- DB Browser for SQLite
- Python
- Google Colab
- Pandas
- Matplotlib

## Project Structure
- `code/` : Python scripts and notebooks
- `screenshots/` : Result screenshots and generated graphs
- `requirements.txt` : Required Python libraries


## Dataset Description

The dataset used in this research was obtained from an encrypted iOS backup for forensic analysis purposes.

Due to privacy and ethical considerations, the original WhatsApp database is not publicly available.

The extracted artifacts include:
- Message content (ZTEXT)
- Message timestamps (ZMESSAGEDATE)
- Sender and receiver identifiers

---

## Methodology

The framework follows these steps:

1. Extract encrypted iOS backup
2. Locate WhatsApp database
3. Open SQLite database
4. Execute SQL queries
5. Convert Apple timestamps into Unix timestamps
6. Organize messages chronologically
7. Generate timeline visualization

---

## Results

### Structured WhatsApp Messages

![Structured Messages](results/figures/table.png)

### Message Timeline Visualization

![Timeline](results/figures/timeline.png)

---

## Key Contributions

- Developed a forensic framework for WhatsApp artifact reconstruction
- Converted Apple timestamps into human-readable format
- Organized forensic artifacts chronologically
- Improved forensic data readability and interpretation

---

## Reproducibility

To reproduce the results:

```bash
pip install -r requirements.txt
python src/timestamp_conversion.py

## Results
The framework successfully reconstructed WhatsApp message timelines and organized extracted records into readable chronological structures.

## Data Availability
Due to privacy and ethical considerations, the original forensic data and backups are not publicly shared.

## GitHub Repository
Add your repository link here.

## DOI
Add your DOI link here after generating it from Zenodo.
