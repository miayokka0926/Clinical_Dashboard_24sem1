# Clinical_Dashboard_24sem1

This project is building with Python and R Shiny.

## Purpose and Goal

This project aims to developing a clinical dashboard utilizing R Shiny, designed display the visualization of a certain clinical database sourced from Redcap. The dashboard offers users the ability to explore the disease of interest, including its distribution across melbourne or Victoria, comparisons of death rates associated with 2 popular medications, as well as analyses of disease prevalence across various variables, including ethnicity and income levels.

Please note that throughout the development, all utilized databases are simulated data to ensure privacy and confidentiality.

## Website Preview
1. Welcome Page:
![Welcome Page Preview](https://github.com/miayokka0926/Clinical_Dashboard_24sem1/blob/main/Picture/Welcome.png "Welcome Page Preview")
By clicking the drop down menu, user are allow to switch between three default example database.

2. Geo-Map and Suburb Info:
![Geo-Map Preview](https://github.com/miayokka0926/Clinical_Dashboard_24sem1/blob/main/Picture/Map.png "Geo-Map Preview")
By hoving on the suburb, user are allow to preview each suburb's info. Once the suburb selected, switch to Local Heatmaps tab and it will show the heatmap for this region.
![Heatmap Preview](https://github.com/miayokka0926/Clinical_Dashboard_24sem1/blob/main/Picture/HM.png "Heatmap Preview")

3. Kaplan-Meier Plot:
![KM Plot Preview](https://github.com/miayokka0926/Clinical_Dashboard_24sem1/blob/main/Picture/KM.png "KM Plot Preview")
The Kaplan-Meier Plot looks at the most popular two medicine in the database.



## Method and Steps
To achieve this, this project is splited into following steps. The related files are named accordingly. View jupyter notebook and R markdown inside the folder for details.

Completed:

  0. Generate stimulated data through Synthea and modify patients' ethnecity group and address information to suit Australia's situation. (Idealy, users should use their own database. This process is only for developers.)

  1. Create Redcap project, fit the generated data into redcap upload template and upload to the desired project through API. For merging and uploading data, refer to 1st intake's work [Redcap Upload](https://github.com/Clinical-Informatics-Collaborative/clinical_dashboards/tree/main/Redcap "Redcap Upload"). There are 3 project in total for demostration: 2 standard project and 1 non-standard project (with wrong column name).

  2. Connect to WEHI R Shiny server and fetch data from Redcap Project using API.

In Progress:

  3. Using MongoDB, establish an intermediary database for faster retrieval of data from the database.
  
  4. Build R Shiny UI and Server and launch the website.

  5. If possible, figure out how to map non-standard project to correct column name so that it can show visualization.

## Q&A
tbc
