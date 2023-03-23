# Reducing Traffic Mortaility EDA

Reducing Traffic Fatalities through Data Analysis

## Project Description

This project aims to investigate how to reduce the incidence of road accidents across the United States by identifying patterns in the demographics of traffic accident victims for each state. The goal is to derive suggestions for a policy action plan by focusing on groups of states with similar profiles, rather than implementing a costly nation-wide plan. To achieve this, the project uses data wrangling, plotting, dimensionality reduction, and unsupervised clustering techniques.

The project uses a dataset originally collected by the National Highway Traffic Safety Administration and the National Association of Insurance Commissioners, which includes information on the number of drivers involved in fatal collisions per billion miles, percentage of drivers involved in fatal collisions who were speeding, percentage of drivers involved in fatal collisions who were alcohol-impaired, and percentage of drivers involved in fatal collisions who had not been involved in any previous accidents.

## Project Steps

    The raw data files and their format: The project starts with an introduction to the data and its sources, followed by a description of the columns and their abbreviations.

    Read in and get an overview of the data: The project reads in the data and provides an overview of its size and structure.

    Create a textual and a graphical summary of the data: The project calculates summary statistics and produces a graphical overview of the data, including histograms and scatterplot matrices.

    Quantify the association of features and accidents: The project computes the Pearson correlation coefficient matrix to quantify the pairwise relationships between the target variable (number of fatal accidents) and the feature variables.

    Fit a multivariate linear regression: The project uses multivariate linear regression to compute the association of the target with each feature while adjusting for the effect of the remaining features.

    Perform PCA on standardized data: The project performs principal component analysis (PCA) on standardized data to investigate the weak association between alcohol consumption and the number of fatal accidents across different states.

## Technologies Used

The project uses Python 3, Jupyter Notebook, and several Python libraries, including pandas, numpy, matplotlib, seaborn, and scikit-learn.

## Getting Started

To run this project, you will need to have Python 3 and Jupyter Notebook installed on your local machine. You will also need to install the necessary Python libraries.

## Contributors

This project was created by Nahmoud Salman as a project for the Data Analysis Internship at Technocolabs Softwares.

## License

This project is licensed under the MIT License.
