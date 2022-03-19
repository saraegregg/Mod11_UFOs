# Module 11 Challenge

---
## UFO Sightings
---

### Project Overview
Dana, a data journalist from McMinnville, Oregon, decides to write about the famous UFO sightings from her howetown and publish her article and a table of UFO sighting data in an HTML page. Her goal is to also include filters that would allow her audience to sift through the extensive data in her table.


### Challenge Objectives
Dana has constructed her HTML page and table, but the next step is adding filters for the following columns:
    - Date   
    - City
    - State
    - Country
    - Shape


### Resources
**Data Sources**
- data.js

**Software**
- Jupyter Notebook 6.4.5
- Python 3.9.7
- Visual Studio Code 1.63.2

### Challenge Results
The code I have written will notice when a new input has been added to any of the text boxes on the left hand side of the HTML page and the cursor removed from that box. This triggers the updateFilters fuction to apply the filters to the table and only display rows that match the critera defined by the text input boxes. 
![FilteredTable.png] (https://github.com/saraegregg/Mod11_UFOs/blob/main/static/images/FilteredTable.png)

When a filter box is cleared of text, that filter is also removed from the table. After removing any filters that may have been added, the entire table is displayed.
![UnfilteredTable.png] ()


### Challenge Summary
One major drawback of the project is the current HTML page is only available locally on a computer with these files. One way to make it publicly accessible would be to use GitHub Pages to publish the page and let users access it in this manner. Another drawback is that, while there is quite a lot of information included in the table, it is certainly not an exhaustive source for UFO sightings--in only covers the month of January in 2010. If we could expand the dataset, it may be more interesting and helpful for the intended audience.

