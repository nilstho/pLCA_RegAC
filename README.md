# pLCA_RegAC
Advancing sustainability: Explore prospective Life Cycle Assessment (pLCA) with data insights. Drive informed decisions for a greener aviation future. This is the repository of the scientific article ["Towards sustainable regional aviation: Environmental potential of hybrid-electric aircraft and alternative fuels"](https://doi.org/10.1016/j.spc.2024.01.013) submitted in [Sustainable Production and Consumption](https://www.sciencedirect.com/journal/sustainable-production-and-consumption). 

This repository captures the needed material to run the prospective LCA for regional hybrid-electric aircraft. Start with Jupyter Notebook 0 and follow the rest of the remaining notebooks. For easier use, we also uploaded some pickle files, which comprise most of the results. Hence, instead of going through all code and calculating everything again, you can use these files directly with the notebook "4_Data_curation_and_visualisation" . However, if you want to reproduce the results, you need to go through all notebooks. The repository entails the following:

Jupyter-Notebooks:
- 0_Premise_setup
- 1_Projects_and_DB_setups
- 2.1_Calculation_of_deterministic_results_2030
- 2.2_Calculation_of_deterministic_results_2040
- 2.3_Calculation_of_deterministic_results_2050
- 3.1_Calculation_of_probabilistic_results_2030
- 3.2_Calculation_of_probabilistic_results_2040
- 3.3_Calculation_of_probabilistic_results_2050
- 4_Data_curation_and_visualisation

LCI databases:
- In BW2 format --> faster
- Excel format

Results:
- pickle files for fast result analysis without rerunning everything in the script
- Excel files for Monte Carlo simulation results and global sensitivity analysis results

Supporting Information:
- pdf file accompanying the article with additional figures, tables and method explanations
