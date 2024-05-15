# Recent increase in asthma mortality in Brazil: a warning sign for the Public Health System.


Authors: Marcos Antunes, Jordana Henz, Mariana Boeira, Simoni Soares, Frederico Friedrich, Paulo Márcio Pitrez

This repository provides functions for importing and analyzing data from the Brazilian mortality information system.

## Packages
The packages used in this study are a combination of tools for data manipulation, analysis, and visualization in R. Here's a brief description of each:

pacman: An R package manager that facilitates the installation, loading, and updating of packages,
gtsummary: A tool for quickly summarizing datasets into beautiful, publication-ready tables,
dplyr: A data manipulation library, providing functions for filtering, selecting, transforming, and aggregating data efficiently,
markdown: A markup language that allows for easy creation of formatted documents, including the ability to embed R code and results elegantly,
forecast: A package for time series modeling and forecasting,
nortest: Provides normality tests in R,
janitor: Facilitates data cleaning in R, providing functions for renaming columns, removing duplicate values, and more,
vroom: A fast package for reading and writing data files in CSV format,
ggplot2: A popular library for creating graphics in R, allowing the construction of complex and custom plots,
ggpubr: A package that provides functions to facilitate the creation of publication-style graphics in ggplot2,
tidyverse: A collection of R packages that work well together for data manipulation and visualization,
readxl: A tool for importing data from Excel files directly into R,
lattice: A library for creating lattice graphics in R,
scales: A package that provides functions for adjusting the scale of axes in plots, aiding in the formatting of axis labels and intervals,
RColorBrewer: A package that provides useful color palettes for graphics in R,
epitools: A package for epidemiological and public health statistics in R.

## Linear regression
Additionally, we employed linear regression as a statistical technique to model the relationship between an independent variable and a dependent variable. It's a way to understand how a change in the independent variable affects the dependent variable. Linear regression is represented by the equation:

𝑌 = 𝛽0 + 𝛽1𝑋 + 𝜀 

Where:
Y is the dependent variable,
X is the independent variable,
𝛽0 is the intercept of the regression line,
𝛽1 is the regression coefficient representing the slope of the regression line, and
ε is the error term.

## Chi-square
After performing linear regression, the chi-square test was applied to assess the significance of the relationship between the variables. This test is useful for determining whether there is an association between two categorical variables.

## Mortality Rate
The asthma mortality rate per 100,000 population is a measure used to express asthma mortality in a given population adjusted for population size. The formula to calculate this rate is:

Asthma Mortality Rate: (Number of Deaths from Asthma/ Total Population) × 100,000

This formula calculates the number of deaths from asthma per 100,000 population, allowing comparisons between different populations regardless of population size. It's an important measure for assessing the impact of asthma in a particular region or period.

## Data dictionary and population informations
The data dictionary can be accessed at the following link: 
-https://opendatasus.saude.gov.br/dataset/sim/resource/b894426e-83dc-4703-91f8-fe90d9b7f8f0.

Population data were calculated based on the 2010 and 2022 censuses available at the following links:
2010 - https://www.ibge.gov.br/estatisticas/sociais/populacao/9662-censo-demografico-2010.html.
2022 - https://www.ibge.gov.br/estatisticas/sociais/trabalho/22827-censo-demografico-2022.html.

