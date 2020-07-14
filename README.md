# Seattle-Police-Salary

My friend sent me an article about average Seattle police salary.  I was curious to see if the article was stating facts, so I followed the citations back to the original data set (https://data.seattle.gov/City-Business/City-of-Seattle-Wage-Data/2khk-5ukd) and turned it into a quick visualization to understand the data better.  Turns out the article was misrepresenting the facts by stating the outliers instead of the average.  **I am not posting the original article as I don't want this to become a political debate.

Orgianl dataset (csv) -> City of Seattle Wage Data
My dataset (csv) -> Updated Wage Data

I added a column to the dataset that grouped the most common job titles together (focusing strictly on the Police Department) using Jupyter Notebook and Pandas.  I exported the new dataset to Tableau and made two simple visualizations.  One representing the average wage of each department funded by the City of Seattle and another showing groupings of job titles within the Polic Department, the average hourly wage and the number of employees in the hourly wage and job grouping.  Both visualations are interactive by scroll over. The firstvisualization highlights the department and average wage, the second highlights details including: department, job title, average wage and number of employees making that wage.
