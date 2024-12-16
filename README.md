# Automated Data Analysis Tool

## Overview

# TDS-Project-2

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Introduction

**TDS-Project-2** is an advanced solution designed to streamline the process of analyzing datasets, generating insights, and visualizing results with minimal user intervention. It supports a wide range of datasets and provides comprehensive reports, including statistical summaries, correlation analysis, and visualizations. Additionally, the tool leverages OpenAI's models to create detailed narrative insights based on the analysis outcomes.

---

## Project Structure

The repository is organized as follows:


### Key Components:
1. **`autolysis.py`**: 
   - The central script for automating data analysis tasks.
   - Includes functions for reading, processing, and analyzing data.
   
2. **`goodreads/`**:
   - Contains tools for analyzing data related to books or Goodreads reviews.
   - Includes scripts for data scraping or sentiment analysis.

3. **`happiness/`**:
   - Focuses on analyzing happiness datasets (e.g., global happiness indices).
   - Provides insights or visualizations based on happiness scores.

4. **`media/`**:
   - Stores visual outputs (charts, graphs, etc.) or media-related files.

---

## Installation

### Prerequisites
1. **Python 3.7 or above** is required.
2. Install the necessary dependencies by running:

   ```bash
   pip install -r requirements.txt
Clone the Repository
git clone https://github.com/im-adamya-vatsalya-sharma-09/TDS-Project-2.git
cd TDS-Project-2

Usage
Running the Main Script
To execute the primary functionality of the project, run the autolysis.py script:

python autolysis.py
Expected Input
The script may require specific input files (e.g., .csv datasets) stored in the respective folders (goodreads or happiness or media).

Output
Outputs include visualizations, processed datasets, or console logs.
Check the media/ folder for graphical outputs or saved media files.

Features
1. Automated Data Analysis
autolysis.py streamlines repetitive analysis tasks.
2. Happiness Index Insights
Analyze global happiness datasets to uncover trends and patterns.
3. Goodreads Data Insights
Analyze data related to books, ratings, and reviews.
4. Visualization Outputs
Produce visually compelling graphs and charts saved in the media/ folder.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
