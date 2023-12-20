Heavy Metal Analysis README

Overview
This repository contains data and analyses related to the concentration of heavy metals in nematode samples from different areas and trophic groups. The primary analysis is conducted in a Jupyter Notebook named Nematode.ipynb. The notebook explores various research questions related to heavy metal distribution, trophic levels, and geographic areas. 

Dataset

The primary dataset used for this analysis is named Nematode.csv. It includes the following columns: 
•	Area: Geographic area where nematode samples were collected (e.g., Bagnoli-Coroglio Bay (contaminated), Gabicce Mare (control)).
•	Trophic group: Trophic level of nematodes (predators of microbes, deposit feerder, microalgal grazers, predators of metazoans).
•	Code: Area-specific code.
•	Nematode individual biomass: Biomass of individual nematodes.
•	Metal concentrations (Cr, Cu, Mn, Ni, Zn): Concentrations of different heavy metals.

Analysis Questions
1.	How do metal concentrations vary across different trophic groups?
Analysis: The notebook utilizes Kruskal-Wallis and Tukey’s post hoc tests to explore variations in metal concentrations among trophic groups.
2.	Are there any significant differences in metal levels between contaminated sediments and control sites? 
Analysis: Investigate metal concentration differences between areas (contaminated vs. control) and trophic group, using Kruskal-Wallis.
3.	Is there a positive correlation between nematode biomass and heavy metal concentration? How is this affected by trophic group?
Analysis: Utilize linear regression models to explore the correlation between nematode biomass and metal concentrations. Assess whether trophic groups influence this correlation.

How to Use
To replicate or extend the analyses:
1.	Clone this repository: git clone https://github.com/rabiasevil/nematode.git
2.	Download the required files:
•	Nematode.ipynb: The primary Jupyter Notebook containing the analysis.
•	Nematode.csv: The dataset with nematode samples and heavy metal concentrations.
Save these files into the same directory as the notebook.
3.	Open Jupyter Notebook in your local environment.
4.	Open the notebook named Nematode.ipynb.
5.	Run each cell sequentially to reproduce the analyses.


Dependencies
The notebook relies on the following Python libraries:
•	Pandas
•	Seaborn
•	Matplotlib
•	Scikit-learn (for Linear Regression Model)
•	Scikit-posthocs
•	Scipy (for statistical tests)
•	Statsmodels (for additional statistical analysis)

To install the required packages, run the following command:
pip install pandas seaborn matplotlib scikit-learn scipy statsmodels scikit-posthocs

