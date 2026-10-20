# Public Transit Convenience Score for Different-Sized Cities Across the U.S.

A data analysis project exploring how convenient public transit is across U.S. cities of different sizes. This repository contains a Jupyter Notebook that analyzes transit accessibility, compares city-level transportation performance, and visualizes patterns across small, medium, and large urban areas.

## Project Description

Public transportation convenience varies widely across cities depending on population size, network coverage, service frequency, and commuter accessibility. This project aims to quantify those differences using a transit convenience score and compare how cities perform relative to one another.

The analysis focuses on key questions such as:

- Which cities have the most convenient public transit?
- How does transit convenience differ by city size?
- What factors contribute to stronger or weaker transit systems?
- Are larger cities always more transit-friendly?

This project is designed as a practical data exploration and storytelling exercise using Python and Jupyter Notebook.

## Repository Contents

- `A03-Transportation-Convenience-Across-US-cities.ipynb` — main notebook containing the data analysis and visualizations
- `README.md` — project overview, setup instructions, and documentation

## Key Features

- City-by-city comparison of public transit convenience across U.S. cities
- Transit convenience scoring framework
- Exploratory data analysis using Python
- Visual summaries of transit quality and performance
- Comparison across small, medium, and large cities
- Reproducible notebook workflow for analysis and presentation

## Why This Project Matters

Transportation is one of the most important factors shaping daily life, access to jobs, affordability, and urban mobility. By comparing transit convenience across cities, this project provides a simple but useful lens for understanding how transportation infrastructure affects urban living.

## Setup Instructions

### Prerequisites

Before running the notebook, make sure you have:

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- `pip` for installing Python packages

### Clone the Repository

```bash
git clone https://github.com/vivatechprogress/public-transit-convenience-score-for-different-sized-cities-across-U.S.git
cd public-transit-convenience-score-for-different-sized-cities-across-U.S.
```

### Create a Virtual Environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### Install Dependencies

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

If additional packages are required while running the notebook, install them as they appear in the notebook imports.

### Launch the Notebook

```bash
jupyter notebook
```

Then open:

```bash
A03-Transportation-Convenience-Across-US-cities.ipynb
```

## Running the Analysis

1. Open the notebook in Jupyter.
2. Run the cells in sequence.
3. Review the data cleaning, scoring, and visualization sections.
4. Modify or extend the analysis if you want to add new cities, metrics, or comparisons.

## Data and Methodology

This project evaluates transit convenience through a scoring approach that considers transportation-related factors such as:

- transit coverage
- route availability
- service frequency
- overall accessibility
- how well transit supports daily city travel

The notebook performs the data preparation, transformation, comparison, and visualization needed to assess these factors.

## Example Workflow

The notebook generally follows this pattern:

1. Import required libraries
2. Load and inspect city transit data
3. Clean and structure the dataset
4. Define or compute convenience metrics
5. Compare cities by size or region
6. Generate charts and summaries
7. Interpret the results

## Project Goals

This repository seeks to:

- highlight differences in public transit convenience across U.S. cities
- provide a clear, data-driven comparison of urban transportation accessibility
- showcase practical Python-based data analysis in a notebook format
- make transit performance analysis understandable and visually engaging

## Potential Extensions

Future improvements could include:

- adding more cities and more recent data
- comparing different years of transit performance
- integrating geographic mapping visualizations
- building a dashboard-style interface
- expanding the scoring model with more transportation factors
- publishing a cleaned dataset alongside the notebook

## Usage

This project is suitable for:

- educational data analysis
- urban mobility exploration
- transportation planning discussions
- portfolio or coursework examples
- quick comparative analysis of city transit systems

## Contributing

Contributions are welcome. If you would like to improve the notebook, expand the analysis, or add new visualizations:

1. Fork the repository
2. Create a new branch
3. Make your improvements
4. Submit a pull request

## License

This repository does not currently include a license file. If you intend to share or reuse the project publicly, consider adding an appropriate open-source license.

## Contact

For questions or collaboration opportunities, visit the GitHub repository:

https://github.com/vivatechprogress/public-transit-convenience-score-for-different-sized-cities-across-U.S.
