# Pandemic Shocks and Fiscal-Monetary Policies in the Eurozone: COVID-19 Dominance During January - June 2020

*Tracing the relationship between Eurozone sovereign spreads and COVID-19 mortality dynamics, accounting for fiscal interventions.*

This repo stores input, output, and code for the June 2020 NBER Working Paper ["Pandemic Shocks and Fiscal-Monetary Policies in the Eurozone: COVID-19 Dominance During January - June 2020"](https://www.nber.org/papers/w27451) by [Yothin Jinjarak](https://www.wgtn.ac.nz/sef/about/staff/yothin-jinjarak) (Victoria University of Wellington); [Rashad Ahmed](https://www.nber.org/people/rashad_ahmed) (University of Southern California); [Sameer Nair-Desai](https://www.nber.org/people/sameer_nair-desai) (University of Southern California); [Weining Xin](https://www.weiningx.com/) (University of Southern California); and [Joshua Aizenman](https://dornsife.usc.edu/cf/econ/econ_faculty_display.cfm?Person_ID=1043595) (University of Southern California).

The master branch hosts the R Markdown and Knitr documents, as well as folders with the initial data; temporary data; visualizations (interactive and static); and regression outputs.

*** Please note, the contents of this repository are very similar to our [previous repo](https://github.com/snairdesai/COVID-19), for the May 2020 NBER Working Paper ["Accounting for Global COVID-19 Diffusion Patterns, January-April 2020"](https://www.nber.org/papers/w27185). ***

# DESCRIPTION OF THE FILES

The relevant R Markdown file is "COVID-Dominance.rmd" which is fully reproducible in RStudio or RCloud. Accompanying the markdown is a knit file of the output ("COVID-Dominance.html"). The Python file "EZcovid.ipynb" provides code to reproduce Figures 1-3 in the working paper.

# DESCRIPTION OF THE FOLDERS

The "data" folder includes all of the initial and manipulated data used in the analysis. Details on where the data was pulled from can be found in the relevant chunks of the Markdown file, in the text documents of the working paper, and in the associated README file. Credit for the raw data goes to all associated sources, which are cited in the paper.

In addition to the data folder, the repository also hosts the "csse_covid_19_time_series", "government_data", and "spreads_data" folders. The data from these folders is also uploaded to the central data folder, but have been included separately for ease of access. These represent our primary raw data files. The first file contains the COVID data pulled from John Hopkins CSSE. The second file contains the government data pulled from the Oxford Government Response Tracker. The last folder contains various raw datafiles used for our projection analysis of Eurozone spreads.

The "output_png" folder includes all of our static figures. All interative HTML figures can be generated using the Markdown file, and viewed in the Knit documents.

The "reg_output" folder includes all of the tables from the regression analysis, which have been clearly labelled for ease of access. You will be able to find where the tables are generated in the markdown file by using the search function.

All folders in the repository are accompanied by a detailed README file explaining the contents.

**CONTACT**

Sameer Nair-Desai 

snairdesa@gmail.com   

Rashad Ahmed   

rashadah@usc.edu                           

Weining Xin

weiningx@usc.edu
