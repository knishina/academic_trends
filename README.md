# academic_trends
## The project can be seen: https://knishina.github.io/academic_trends/

### Summary.
Data from 2014 was extracted from two databases: the U.S. Census Bureau's American Community Survey, and the Behavioral Risk Factor Surveillance System (BRFSS). Data for the percent population attaining either a high school or undergraduate degree were obtained from the Census Bureau. Data for the percent survey respondents indicating serious difficulty concentrating, remembering, or making decisions were obtained from the (BRFSS).  The data were cleaned with Pandas and visualized via D3.js.

### Contents.
There are four relevant files and one folder for this mini-project.
- `Raw Data` &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Folder with data from BRFSS and the Census Bureau
- `app.js` &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;JavaScript code that allows for D3 visualization.
- `index.html` &nbsp; &nbsp; &nbsp; HTML.
- `mind_data.csv` Cleaned data.
- `style.css` &nbsp; &nbsp; &nbsp; &nbsp;CSS for HTML.

<br />

### Features.
This is a simple web page that uses D3.js to visualize the differences between survey respondents with a high school diploma and those that completed an undergraduate degree.  The bubble plot has two colors: blue for those that completed up to a high school degree, and purple for those that completed up to an undergraduate degree.  Trend lines associated with both types of data.  The data can be selected with the check boxes in the upper left of the page.  Additionally, a text box will be displayed when hovering over each bubble.  Information displayed includes: the state name, percent memory loss, and percentage of individuals that completed the education level.

![Chart with both data]()
![Chart with one data type]()
