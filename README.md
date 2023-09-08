# Adsorption Kinetics Project

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Input Parameters](#input-parameters)
4. [Usage](#usage)
5. [Results](#results)
6. [Getting Started](#getting-started)
7. [Contributing](#contributing)
8. [License](#license)

---

## 1. Introduction<a name="introduction"></a>

Welcome to the Adsorption Kinetics project! This project aims to solve and visualize the kinetics of adsorption using two different models: PVSDM (Pore Volume-Surface Diffusion Model) and QPVSDM (Quadratic Pore Volume-Surface Diffusion Model). These models help analyze how adsorbates are taken up by adsorbents over time. This README provides a detailed overview of the project, input parameters, usage instructions, and more.

## 2. Project Overview<a name="project-overview"></a>

The primary objective of this project is to simulate and compare the PVSDM and QPVSDM models with experimental data. The project requires users to input various parameters and experimental data to perform the simulations. After the calculations, the app generates plots to visualize the results and compare the models with the experimental data.

## 3. Input Parameters<a name="input-parameters"></a>

To run the simulation successfully, you need to provide the following input parameters:

1. **Final Time (𝑡𝑓):** The total time for the simulation in minutes.
2. **Omega (ω):** The dimensionless adsorbent dosage.
3. **Biot Number (Bi):** A dimensionless number used to characterize the relative importance of external mass transfer to internal mass transfer.
4. **Mean Radius of Adsorbent (𝑅):** The mean radius of the adsorbent in centimeters.
5. **Pore/Surface Diffusivity Ratio (𝐷sp):** The ratio of pore diffusivity to surface diffusivity.
6. **Pore Diffusivity (𝐷p):** Pore diffusivity in square centimeters per second.
7. **Adsorbent Porosity (ε):** The porosity of the adsorbent material.
8. **Langmuir Parameters (𝛼 and 𝛽):** The dimensionless Langmuir parameters.

## 4. Usage<a name="usage"></a>

To use the app, follow these steps:

1. **Input Parameters:** Enter the required input parameters as specified above.

2. **Experimental Data:** Provide the experimental adsorption data in a suitable format. This typically includes data points of adsorption at various time intervals.

3. **Run the Simulation:** Execute the simulation to calculate adsorption kinetics using both PVSDM and QPVSDM models.

4. **Plot Results:** The app will generate plots comparing the simulation results of both models with the provided experimental data.

## 5. Results<a name="results"></a>

The app produces visual results that include:

- A plot comparing the PVSDM (Δ𝑉-Δ𝑡) and QPVSDM (Quadratic Δ𝑉-Δ𝑡) model predictions with the experimental data.

These results help you evaluate how well the chosen adsorption models fit your experimental data.

## 6. Getting Started<a name="getting-started"></a>

To get started with this project, follow these steps:

1. Clone this repository to your local machine. Alternatively, you can download the project.

2. Follow the usage instructions mentioned above to run the app with your specific input data.

## 7. Contributing<a name="contributing"></a>

If you would like to contribute to this project or report issues, just click on the "Need help?" button and e-mail me. Feel free to reach out if you have any questions or need further assistance with this Adsorption Kinetics project. Happy simulating and analyzing!

---
Last Update: September 2023
