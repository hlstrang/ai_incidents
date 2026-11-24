# Headlines of AI Incidents
## Data Obtained from Kaggle
[Data](https://www.kaggle.com/datasets/eleanorharris7/headlights-ai-incident-library)

[License](https://creativecommons.org/licenses/by-nc/4.0/)

## About
This dataset contains information about publically-available real-world AI incidents documented between 2015-2026. Each title has been tagged with the main human behaviour behind the incident.

## Tools
    - Python (pandas, ipywidgets, matplotlib)
    - Git & GitHub
    - Binder

## Data Cleaning
The first thing I did was drop the columns I didn't need (incidentId and url) and convert the year column to numeric instead of strings. Then I manually added company data for each title, by scanning for companies/people responsible. Where companies were kept anonymous I added 'Unnamed company' or 'Unnamed persons'.

## Visualisations
I then created various bar graphs showing the most common companies involved, the most common industries affected, and the most common companies involved for the top three countries (US, Australia, UK).

## Interactive Lookup Tool
The final thing I did was create an interactive tool to explore the different AI incidents by your preferred metric. You can search for individual companies, behaviours, or industries and see the headlines of the incidents present. To use this tool, see the notebook on Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hlstrang/ai_incidents/HEAD?urlpath=%2Fdoc%2Ftree%2Fworkbook.ipynb)