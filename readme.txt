
# Multi-Cloud Resource Allocation using CloudAnalyst

This project implements and analyzes resource allocation strategies in a multi-cloud environment using CloudAnalyst. The repository contains source code, configuration files, and Jupyter notebooks for simulating and evaluating different load-balancing and resource-allocation techniques.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

CloudAnalyst** is a simulation tool for modeling and analyzing cloud computing environments. This project extends CloudAnalyst to study and compare static and dynamic load balancing strategies for resource allocation across multiple cloud data centers.

---

## Features

- Simulation of multi-cloud environments
- Static and dynamic load balancing algorithms
- Jupyter notebooks for experiment tracking and visualization
- Modular and extensible codebase

---

## Repository Structure

```
.
├── .settings/                # IDE and project settings
├── classes/                  # Compiled Java classes
├── config/                   # Configuration files for simulations
├── jars/                     # Required JAR dependencies
├── javadoc/                  # Generated Java documentation
├── resources/                # Additional resources (images, data, etc.)
├── source/                   # Main Java source code
├── dynamic_load_balancwr.ipynb   # Jupyter notebook for dynamic load balancing experiments
├── static_multi_DC.ipynb         # Jupyter notebook for static multi-data center experiments
├── run.bat                   # Batch file to run the project
├── readme.txt                # Additional project notes
├── .classpath                # Java classpath file
├── .project                  # Eclipse project file
└── .DS_Store                 # macOS system file
```

---

## Getting Started

### Prerequisites

- Java (JDK 8 or above)
- [CloudAnalyst](http://www.cloudbus.org/cloudsim/)
- Jupyter Notebook (for running `.ipynb` files)
- (Optional) Eclipse IDE for Java development

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ritchi-e/VCC_Project.git
   cd VCC_Project
   ```

2. **Set up dependencies:**
   - Ensure all required JAR files are present in the `jars/` directory.
   - Import the project into your IDE (Eclipse recommended) using `.project` and `.classpath`.

3. **Run the simulation:**
   - Use `run.bat` (Windows) or configure your IDE to run the main class in the `source/` directory.

4. **Jupyter Notebooks:**
   - Open and run `dynamic_load_balancwr.ipynb` or `static_multi_DC.ipynb` for experiment analysis.

---

## Usage

- Modify configuration files in the `config/` directory to set up your simulation parameters.
- Run simulations using the provided batch file or through your IDE.
- Analyze results using the Jupyter notebooks for visualization and comparison.

---

## Acknowledgements

- [CloudAnalyst](http://www.cloudbus.org/cloudsim/)
- [CloudSim](http://www.cloudbus.org/cloudsim/)

