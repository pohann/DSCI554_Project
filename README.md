# DSCI 554 Project

Project link: http://pdms.usc.edu/dsci-554-projects/project-hotshot-crew-554/

## Team

Team name: Hotshot Crew 554 :fire:

Team members:

- Asumi Suguro <suguro@usc.edu>  :woman_firefighter:
- Luke Nelson <lukenels@usc.edu> :firefighter:
- Kaile Huang <kailehua@usc.edu> :woman_firefighter:
- Po-Han Chen <cpohan@usc.edu> :firefighter:

---

## Project Summary

According to the PNAS (Proceedings of the National Academy of Sciences of the United States of America), forest fires in the western United States have been increasing in both size and severity for several decades. These increases have been attributed to human activities and climate change. With all of the recent fires the US has been experiencing, this information is top of mind for health authorities, fire departments, environmental organizations, and even the common person such as you or me.

The goal of our project is to first provide users with an understanding of the recent growth in wildfire incidence and severity. Secondly, we will promote action over reaction as it relates to fighting wildfires. Historic patterns and relationships among wildfire causes, seasonality, location, and spending support the notion that being proactive towards preventing fires is achievable. This approach of working to prevent wildfires should be given just as much weight and attention as is given to putting out fires that have already started.

We are utilizing a [Kaggle SQLite database](https://www.kaggle.com/rtatman/188-million-us-wildfires "1.88 Million US Wildfires") referred to as the Fire Program Analysis fire-occurrence database (FPA FOD). This database contains data surrounding wildfires that occurred in the United States from 1992 to 2015. It includes 1.88 million geo-referenced wildfire records, and represents a total of 140 million acres burned during this 24 year period.

---

## Contributions

## Proposal presentation

- [Asumi Suguro](mailto:suguro@usc.edu) set up Google doc for team collaboration and prepared slides 6-8.
- [Luke Nelson](mailto:lukenels@usc.edu) prepared slides 1-3.
- [Kaile Huang](mailto:kailehua@usc.edu) prepared slides 9-10.
- [Po-Han Chen](mailto:cpohan@usc.edu) prapred slides 4-5 and updated files on project repo.

## Final presentation

- [Asumi Suguro](mailto:suguro@usc.edu) prepared slides 6-8.
- [Luke Nelson](mailto:lukenels@usc.edu) prepared slides 1-3.
- [Kaile Huang](mailto:kailehua@usc.edu) prepared slides 9-10.
- [Po-Han Chen](mailto:cpohan@usc.edu) prepred slides 4-5 and put together the Sozi presentation.

## Paper

- [Luke Nelson](mailto:lukenels@usc.edu) outlined, compiled, and wrote the essay.
- [Kaile Huang](mailto:kailehua@usc.edu) provided chart descriptions for her respective plots and helped proofread.
- [Po-Han Chen](mailto:cpohan@usc.edu) provided chart descriptions for his respective plots and helped proofread.
- [Asumi Suguro](mailto:suguro@usc.edu) provided chart descriptions for her respective plots and helped proofread.

## Demo

- [Asumi Suguro](mailto:suguro@usc.edu) calculated fire counts by year and joined it with the funding dataset. created funding charts and conclusion page
- [Luke Nelson](mailto:lukenels@usc.edu) created the interactive D3 Layout radar plot, helped create and format the Home tab, and did the data pre-processing for the seasonality bar chart
- [Kaile Huang](mailto:kailehua@usc.edu) did data pre-processing to convert original data from Kaggle, created the responsive stacked bar chart and the mapbox map
- [Po-Han Chen](mailto:cpohan@usc.edu) generated wildfires geojson data with Python program written by Kaile and plotted the two d3 maps. helped modifying home page, overall aesthetic theme 
and layout
## Video

- [Asumi Suguro](mailto:suguro@usc.edu) spoke about plots created & conclusion
- [Luke Nelson](mailto:lukenels@usc.edu) spoke about plots created
- [Kaile Huang](mailto:kailehua@usc.edu) spoke about plots created and editted the final video
- [Po-Han Chen](mailto:cpohan@usc.edu) spoke about plots created & instroduction

### List of visualizations
| Requirement                            | Label        |
| -------------------------------------- | ------------ |
| responsive d3 chart                    | responsive   |
| interactive d3 chart                   | interactive  |
| d3 chart with an animated transition   | animated     |
| d3 layout                              | layout       |
| d3 map                                 | map          |
| Mapbox map                             | mapbox       |
Table 1: Table of minimum requirements, 1 of each category is required.

In Table2, list all the charts and tables in your pages including minimum requirements labels when applicable.
| Page name | Chart description | Libraries used | Requirement label |
| --------- | ----------------- | -------------- | ----------------- |
| Historic Fire Map | D3 map  | d3 | map, interactive   |
|Federal Funding  |  Dual-axis chart  |  d3  |   animated      |
|  Federal Funding  |    Scatter Plot  |    d3    |   interactive     |
|  Historic Fire Counts    | Mapbox Map   |   Mapbox |mapbox     |
|  Fire Causes |    Radar Chart   |     d3 |  layout, interactive   |
| Fire Causes |  Bar Chart     |    d3  |    responsive   |
Table2: Table of visualizations

### Additional Notes:
* Bootstrap was implemented in the Federal Funding page of our project
