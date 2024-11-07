# belly-button-challenge

Background
This challenge is aimed to build a user friendly interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Description
1 - Reading the data

We used the D3 library to read samples.json in samples.json from the provided url.

2 - Building the Bar Chart

We created a horizontal bar chart with a drop down menu to display the top 10 OTUs (Operationl Taxonomy Units) found in the selected sample.

3 - Building the Bubble Chart

We created a bubble chart to display alls OTUs for the selected sample.

4 - Displaying the Metadata

We created a function called buildMetadata that fetches metadata corresponding to the selecrted sample and display the demographic information for the selected sample.

5 - Updating plots based on Sample selection

We ensured that all plots are updated dynamically each time a new sample is selected from the dropdown menu using the optionChanged function.

6 - Deploying the dashboard

We deployed the dashboard using GitHub where the code reads the data file and dynamically populates the page using Plotly when a sample is selected in the dropdown menu.

Collaborated with some claamates for this challenge

Dashboard
