# Geosemantics

Project Overview
This project investigates the geosemantics of violent places during INEC activities, utilizing natural language processing (NLP) and geospatial analysis. By analyzing textual data related to electoral violence and mapping the locations, we aim to provide insights into the spatial distribution of violence and its contextual semantics.

Objectives
Data Collection and Preprocessing:

Collect and preprocess textual data related to INEC activities and associated violent incidents.
Annotate the data for named entity recognition (NER) tasks.
Geosemantic Analysis:

Use SpaCy for NLP tasks to extract and classify entities related to violent events.
Implement geolocation libraries to map the extracted locations.
Visualization:

Create interactive maps to visualize the geospatial distribution of violent incidents.
Use visual tools to highlight patterns and clusters of violence.
Methodology
Data Collection and Preprocessing:

Textual data is collected from various sources, focusing on reports and news articles about INEC activities and violence.
Data is preprocessed and annotated for entity recognition using SpaCy.
Geosemantic Analysis:

SpaCy is used to load the annotated data and perform NER to extract relevant entities such as locations and event descriptions.
GeoNames and other geolocation libraries are employed to convert extracted location names into geographical coordinates.
Visualization:

Folium is used to create interactive maps displaying the locations of violent incidents.
Entities are visualized on maps to show spatial patterns and identify areas with high violence frequency.
Results
Extracted and classified entities related to violent events during INEC activities.
Mapped the geospatial distribution of these events, revealing clusters and patterns of violence.
Created interactive visualizations to aid in understanding the geographical context of electoral violence.
