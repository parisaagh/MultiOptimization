# Multiobjective Crashworthiness Optimization for Vehicle Design  
**Surrogate Model-Based Approach for Frontal Crash Scenarios**  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  

---

## 📜 Overview  
This repository presents a **multiobjective optimization framework** for automotive crashworthiness design, addressing the challenges of high nonlinearities in vehicle crash simulations. The methodology integrates surrogate modeling and evolutionary algorithms to optimize vehicle weight, acceleration characteristics, and toe-board intrusion during frontal collisions. Designed for automotive engineers and researchers, this framework enables efficient exploration of Pareto-optimal solutions under full frontal and 40% offset-frontal crash conditions.

---

## 🔑 Key Features  
✅ **Multiobjective Optimization**:  
- Simultaneously minimizes **vehicle weight**, **acceleration peaks**, and **toe-board intrusion**  
- Balances safety and structural efficiency  

✅ **Advanced Surrogate Modeling**:  
- Response surfaces with **linear/quadratic basis functions**  
- **Optimal Latin Hypercube Sampling** (OLHS) for design space exploration  
- **Stepwise regression** for robust metamodel formulation  

✅ **Evolutionary Optimization**:  
- **Nondominated Sorting Genetic Algorithm (NSGA-II)** for Pareto front generation  
- Validated on full-scale vehicle crash scenarios  
