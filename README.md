# PROJECT DESCRIPTION #
This project (schachtj/nashville-socioeconomic-emergencyresponse-analysis) entails an analysis of the relationships between Socioeconomic Data and Emergency Response Incidents in the Nashville, TN area (Davidson County) relative to geographic location. It analyzes datasets with Nashville area census/economic data, incidents data, and geospatial data. These datasets are not provided within this repository since not all of it is public available. 

## Topics ##
The following topics are covered in census-incidents.ipynb:
- Frequency of incidents by census tract across Nashville. 
- Temporal analysis of accidents by month across Nashville. 
- Response Time Distribution on Incidents across Census Tracts 
- Demographic Correlation on the incidents and response time distribution

Notable Conclusions for each of these topics are described at the end of that topic's respective section. Final Conclusions across all topics are located towards the bottom of the file.


## Technologies ##
This project is visualized within a Jupyter notebook (Python 3.8, developed within a conda environment) and employs Amazon S3, Amazon Athena (queries done in SQL syntax), GeoPandas, and Plotly. 

### Additional Notes ###
- For the census-incidents.ipynb, many of the visualizations do not show up in the actual notebook. As a result, each of these 18 images have been included in the repository in html form; each can be seen by accessing the file at ./census\_figures/{path} within the corresponding fig.write_html({path}) command in the Jupyter notebook.
- Project Ownership: This repository contains my (Tim Schachner's) individual contributions to a broader group project, but the findings stand alone as their own discoveries. 
