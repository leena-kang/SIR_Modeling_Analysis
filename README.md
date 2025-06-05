# Modeling COVID-19 Outbreaks with the SIR Framework
### UCSD Math 111A Final Project 

This project explores the effectiveness of the classical Susceptible-Infected-Recovered (SIR) model in
capturing and predicting the spread of the COVID-19 virus. While the SIR model is mathematically
simpler and widely used in epidemiology, its underlying assumptions (such as homogeneous mixing and
fixed parameters) raise questions about its applicability to real-world, stochastic disease dynamics.
We begin by deriving the SIR model and simplifying it through dimensional analysis, introducing the
basic reproduction number R0 to understand its role in outbreak behavior. The system of differential
equations is then solved numerically using Python to simulate disease trajectories under different
parameters. To reflect real-world interventions, we extend the model by incorporating a small-scale
vaccination term and apply regular perturbation methods to quantify its effects. Finally, using
a publicly available COVID-19 cases across the United States from John Hopkins University, we
perform parameter estimation by fitting the model to real infection trends, evaluating its predictive
capability. By combining theoretical modeling and empirical data fitting, this study assesses the SIR
model’s strengths and limitations, while exploring how even low-rate interventions can shift epidemic
outcomes.

Here, we used publicly available COVID-19 data repository by the [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19). This repository offers comprehensive records of confirmed cases, deaths, and recoveries, compiled from various global and local health authorities. Refer to the link/repo for more details about documentation. 