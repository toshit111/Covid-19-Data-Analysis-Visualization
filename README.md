# Covid-19-Data-Analysis-Visualization

## Project Overview

This project involves analyzing COVID-19 vaccination data for various states in India. The analysis includes visualizations of vaccination distributions by gender, dose type, and state-wise comparisons. The primary tools used in this project are Python, Pandas, Matplotlib, Seaborn, and Plotly.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Dataset

The dataset used in this project contains information on the number of first and second dose vaccinations, as well as the gender distribution (male and female) for different states in India. The data is stored in a CSV file.

| State             | First Dose | Second Dose | Male     | Female   |
|-------------------|------------|-------------|----------|----------|
| Andhra Pradesh    | 14000000   | 8000000     | 6000000  | 7000000  |
| Arunachal Pradesh | 3000000    | 1700000     | 1200000  | 1700000  |
| ...               | ...        | ...         | ...      | ...      |

## Installation

To run this project, you need to have Python installed on your system. Follow the steps below to set up the environment and install the necessary libraries.

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/covid-vaccination-analysis.git
   cd covid-vaccination-analysis

2. **Create a virtual environment (optional but recommended):**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
3. Install the required libraries:

   ```sh
   pip install pandas numpy matplotlib seaborn plotly

   
## Usage

1. Place the coviddata.csv file in the project directory.
2. Run the analysis script:
   ```sh
   python analysis.py
3. The script will generate various plots and visualizations for the vaccination data.


## Visualizations

Gender-based Vaccination Distribution

Dose-based Vaccination Distribution

State-wise Vaccination Doses

Male and Female Vaccinations by State

Vaccination Ratio (First Dose to Second Dose) by State

## Results
The analysis provides insights into the distribution of vaccinations across different states in India, highlighting the gender-based distribution and the ratio of first to second dose vaccinations.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -m 'Add new feature').
5. Push to the branch (git push origin feature-branch).
6. Create a new Pull Request

## Contact
If you have any questions or suggestions, feel free to contact me at toshitfirake2003@gmail.com.
