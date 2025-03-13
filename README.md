# Transportation and Mobility Changes in the UK During COVID-19

## Authors
Julie Dawkins, Ruyan Yu, Cassandra Zhang

## Overview
This project analyzes the impact of COVID-19 on transportation and mobility in the United Kingdom, focusing on public transit usage and its relationship with economic indicators such as retail, grocery, and workplace mobility.

## Data Sources
- **Google Community Mobility Reports**: Provides data on movement trends across different categories, including retail, grocery, workplaces, and transit stations.
- **UK Rail Station Usage Data**: Contains annual passenger entries and exits at UK train stations.
- **ISO Codes for UK Subdivisions**: Used to merge datasets for spatial analysis.
- **UK Regional Boundaries & Train Station Locations**: Additional geographic data for visualization.

## Research Questions
1. How did COVID-19 impact public transport usage in the UK?
2. What stations saw the largest decrease in usage, and how did they recover over time?
3. What regions experienced the largest impact in other forms of mobility?
4. Is there a correlation between public transit usage and mobility in retail, grocery stores, and workplaces?

## Getting Started
### Setting Up the Environment
To install all dependencies, download the environment.yml file from the repository and run:
```conda env create -f environment.yml
```
This will create a new Conda environment with the necessary dependencies.
To activate the environment, run:
```conda activate your-env-name
```
(Replace your-env-name with the actual environment name from environment.yml or specify your own name using --name my_new_env.)
If you already have an environment and want to update it:
```conda env update --name existing_env --file environment.yml --prune
```

### Running the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open and execute the analysis notebooks in `notebooks/`.

## Results Summary
- Public transit usage declined by 70-90% across UK regions in 2020.
- London and Scotland had the largest decreases in mobility.
- Mobility trends in retail, grocery, and workplaces strongly correlated with transit station usage, indicating a relationship between decreased public transit and decreased foot traffic in retail and grocery stores.
- Regression analysis confirmed a positive relationship between transit recovery and economic mobility indicators.


## Contact
For questions or contributions, reach out via GitHub Issues or email [julie.l.dawkins@gmail.com].

