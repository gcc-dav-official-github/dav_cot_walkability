### Toronto Walkability Project
The City of Toronto Walkability Assessment was a collective effort by the City of Toronto's Information and Technology Division's Data Analytics and Visualization team (DAV) and the City of Toronto's Transportation Services Division. The project aimed to construct and assess a pedestrian walkable network that would be used further to generate an analytical lens for the assessment of walkability across the City of Toronto. The primary purpose of this project was to identify and analyze characteristics across the following domains:
* mode share for walking by census tract,
* walkability,
* economic impact of walkability,
* growth in the City of Toronto,
* vulnerable/social equity lens,
* streetscape quality,
* identify areas/locations for prioritizing pedestrian improvements,
* develop new tools for prioritization for city infrastructure investments & service improvements, and
* develop decision-support system for implementing new projects for minimum sidewalk design standards.

### Data Collection
Data collection took place between August and September 2018. Data analysts examined all available datasets, compiled them into an integrated resource, and undertook an extensive quality assurance and control process consisting of automated and manual checks to ensure the data is suitable for the task at hand.

### Data Preparation
The methodological approach for this study was to create a pedestrian network (based on sidewalk centerlines), assess the inventory of pedestrian-assets (e.g., sidewalks, crosswalks, pedestrian controlled crossings) city-wide, and determine the walkability of various amenities relevant to the lived experiences of residents across the city. The focus was placed on topological consistency over spatial accuracy. Meaning that the sidewalk centerlines are not necessarily spatially located along with the actual locations of the sidewalk geographically, but the connections between different sidewalk segments were maintained as being a higher priority.

### Walkability
Walkability has been calculated to determine how-walkable a particular area is in relation to pedestrian access to various amenities and socio-demographic characteristics. In Toronto, several communities have lower-walkability when walking to schools. For example, West Humber-Clairville, Humber Summit, Briar Hill-Belgravia, Milliken east, Islington-City Centre West (southern areas), the eastern portion of York University Heights, Clairlea-Birchmount (north), southern parts of West Hill, the eastern part of Dorset Park neighbourhoods, some parts of Waterfront Communities-The Island and Niagara.

### About the Data
This archive contains the final spatial data used for the Toronto Accessibility Analysis project. The pedestrian network (pednet) file contains the following attributes.  

__PEDNET COLUMN DESCRIPTIONS__
* __FID__: unique identifier
* __Shape__: geometry of segment
* __OBJECT_ID__: unique identifier
* __road_type__: segment road type
* __sdwlk_code__: segment sidewalk code
* __sdwlk_desc__: segment sidewalk code description
* __crosswalk__: boolean, crosswalk status
* __cwalk_type__: crosswalk type flag
* __px__: traffic signal or pedestrian control device unique ID number
* __px_type__: crosswalk control flag
* __length__: length of segment

The table below provides a sample of the contents of the pednet shape file.
![alt text](Pednet.JPG)

__PEDNET VALUES__ 
The pednet attribute values are provided below.

Road types include Access Road, Collector, Laneway, Local, Major Arterial, Minor Arterial, Other, Pathway, Pending, Trail and Walkway. Pending roads have not been classified by the Transportation Services Division.

Sidewalk code and descriptions include the following;
1 = Sidewalk on south side only/Sidewalk on south side; partially on other side
2 = Sidewalk on north side only/Sidewalk on north side; partially on other side
3 = No sidewalk on either side
4 = Sidewalk on west side only/Sidewalk on west side; partially on other side
5 = Sidewalk on east side only/Sidewalk on east side; partially on other side
6 = Roadway under development/Roadway under development; some sidewalk present
7 = Sidewalk on both sides
10 = Laneway without any sidewalks
11 = City walkway
12 = N/A
13 = Not applicable

Crosswalk is a boolean value where true is a crosswalk and 0 is not a crosswalk.

Crosswalk types are only populated for those sements identified as crosswalks. Crosswalk types include the following;
ns = crosswalk is not controlled by traffic light/pedestrian crossover light
pc = crosswalk is controlled by pedestrian crossover light
ts = crosswalk is controlled by traffic light
null = line segment is not a crosswalk

Px types are only populated for those sements identified as crosswalks. Px types include the following;
pc = crosswalk is controlled by pedestrian crossover light
ts = crosswalk is controlled by traffic light

### Research Question Definitions ###
Walk times to closest TTC stops 
from every 
### Analysis and Visualization ###
Step 1 - clean

### Conclusion and Next Steps ###