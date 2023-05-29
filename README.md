# leaflet-challenge
Earthquake Visualization with Leaflet
This project aims to visualize earthquake data using the Leaflet library. The data is sourced from the United States Geological Survey (USGS) GeoJSON Feed, which provides updated earthquake data in JSON format. The visualization includes plotting earthquakes on a map, where the size of the markers represents the magnitude of the earthquake and the color represents the depth.

Prerequisites
To run this project, you will need:

Python 3
folium library (install using !pip install folium in a code cell)
Please note that I am using Google Colab in Safari for this project due to compatibility issues with other tools and libraries on my Apple laptop.

Instructions
Visit the USGS GeoJSON Feed page.
Choose a dataset to visualize, such as "All Earthquakes from the Past 7 Days".
Copy the URL of the JSON representation of the dataset.
Open the provided Jupyter notebook in Google Colab.
Replace the data_url variable in the notebook with the URL of the chosen dataset.
Run the notebook cells to import the necessary libraries and create the earthquake visualization.
The visualization will be displayed in the notebook, showing the plotted earthquakes with markers reflecting their magnitude and depth.
Click on a marker to view additional information about the earthquake.
Optional: Tectonic Plates Data
To further enhance the visualization, you can choose to plot tectonic plates data alongside the earthquakes. The tectonic plates data can be found at https://github.com/fraxen/tectonicplates. You can follow the same steps as above to include the tectonic plates data in the visualization.

Please note that due to the limitations of Google Colab in Safari, there might be some restrictions in the interactivity of the map. For the best experience, it is recommended to run the project locally using a compatible code editor or IDE.
