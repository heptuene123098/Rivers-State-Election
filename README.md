# Rivers-State-Election
Outlier Detection in Election Data Using Geospatial Analysis


Task Overview:

Dataset Preparation:

Dataset on Rivers state election
Included longitude and latitude values for each polling unit or ward using Awesome table extension on google sheets as the geocoding techniques.

Neighbour Identification:
Identified neighboring polling units based on geographical proximity within a defined radius (e.g., 1 km) using python

Outlier Score Calculation: was carried out using python
Compare votes each party received with those of neighboring units
Calculate an outlier score based on vote deviations
Record outlier scores with respective parties and neighboring units


Sorting and Reporting: was carried out using python
Sort dataset by outlier scores to identify significant outliers
Provide a detailed report on methodology and findings
Highlight top 3 outliers and their closest polling units, explaining why they are considered outliers

Tips:
Utilize geocoding techniques like Google Maps Geocoding API or OpenCage Geocoding API
Calculate geodesic distance to determine neighboring units
Visualize results with maps and charts

Deliverables:
Cleaned dataset with longitude and latitude values and calculated outlier scores
Sorted list of polling units by outlier scores for each party
Detailed outlier detection report with methodology, findings, examples, and visualizations
