# Solow Growth Model and Intertemporal Optimization

## **Project Overview**
This repository contains an analysis of economic growth using the **Solow Growth Model** and intertemporal consumption optimization. The project explores how savings, depreciation, capital accumulation, and productivity influence long-term output and individual consumption decisions. The analysis is performed using real-world data from France and includes numerical simulations of capital per worker, GDP growth, and consumption smoothing behavior.

## **Repository Structure**
```
/Project2
│── France Data.csv                # GDP, capital stock, and labor force data for France
│── Project2 Part 1 code.R         # Solow Growth Model (Part 1)
│── Project 2 Part 2 code.R        # Solow Growth Model (Part 2) - Calibration & Simulation
│── Project 2 Part3.R              # Solow Model - Simulated vs Actual Output
│── Project 2 Part4.py             # Intertemporal Optimization (Python)
│── LW Project 2 Part 4.ipynb      # Jupyter Notebook for Intertemporal Optimization
│── README.md                      # Project documentation
```

## **How to Run the Scripts**

### **Solow Model Simulation (R)**
To simulate the Solow Growth Model:
1. Install required R packages (`tidyverse`, `ggplot2`, `dplyr`):
   ```r
   install.packages(c("tidyverse", "ggplot2", "dplyr"))
   ```
2. Place `France Data.csv` in the same directory.
3. Run the R script in RStudio or use:
   ```r
   source("Project2 Part 1 code.R")
   ```

### **Intertemporal Optimization (Python)**
To solve the intertemporal consumption optimization problem:
1. Install required Python packages:
   ```sh
   pip install numpy scipy pandas
   ```
2. Run the script from the terminal:
   ```sh
   python Project 2 Part4.py
   ```

## **Results and Insights**

### **Solow Growth Model Findings**
- **Capital per worker convergence:** The model shows that France’s capital per worker is slowly moving toward its steady-state level.
- **Sensitivity Analysis:** Adjusting savings rates, capital elasticity, and depreciation affects the speed of convergence and steady-state GDP.
- **Comparison to Actual GDP:** While the model follows general GDP trends, discrepancies suggest that productivity growth (TFP) plays a significant role in real-world economic fluctuations.

### **Intertemporal Consumption Optimization Findings**
- **Consumption smoothing:** Consumers adjust savings to offset changes in future wealth, maintaining a stable consumption path.
- **Higher patience (β) increases future consumption:** More patient consumers delay consumption, increasing savings.
- **Higher interest rates encourage savings:** Rising interest rates lead consumers to save more, shifting consumption to the future.

## **Policy Implications**
- Interest rate policies significantly influence saving and consumption behavior.
- Productivity growth is crucial for long-term economic expansion.
- Investment incentives could be leveraged to accelerate capital accumulation and economic convergence.



