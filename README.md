# UFO
## Overview of Analysis
The purpose of this analysis is generate a dynamic webpage that allows the user to filter elements of the UFO sightings dataset. We were able to construct the webpage using HTML and added aesthelics with CSS and Bootstrap. Utilized JavaScript to to build the functions, creating the actual tables and generating the filtering functions. 


## Results
For the deliverable, we must create a web based filter using the html file, data.js and app.js. We are filtering on the date, city, state, country, and shape of object. We have created a function to loop through the dataset searching for criteria that match the search criteria.

Filtering Criteria:

![image](https://user-images.githubusercontent.com/99375741/171054014-e8d9621c-a6b9-4d48-80ac-b6b388ba7f9b.png)

To ensure the filtering function works on Dana's webpage, we filtered the state to "tx" and the shape to "light". Once we hit enter, we observe the two entires in Texas that were lights only.

Texas/light filter:
![image](https://user-images.githubusercontent.com/99375741/171054515-690a670f-79dd-4740-b9dc-42bd8b880006.png)

## Summary

### Drawback
On of the drawbacks for this design resides in the filtering feild on the webpage. The feild requires a specific formatting to return the results you are looking for and if the user inputs the parameter incorrectly, you may return misleading results.

Input date as "01/01/2010" instead of "1/1/2010", returing an empty table.

Incorrect:
![image](https://user-images.githubusercontent.com/99375741/171055836-a7413d33-f72a-4b9e-8232-37f307963cbd.png)

Correct:
![image](https://user-images.githubusercontent.com/99375741/171056027-10e682f0-e316-4e0c-9d24-0be84c606eae.png)

### Recommendations
1. It would be recommended to develop an ability to aggregate the values in order to gain a better prospective of the data. As it stands, it is difficult to draw any conclusions based on the table generated. 
2. Add a filter to allow for the filtering of the duration feild.

