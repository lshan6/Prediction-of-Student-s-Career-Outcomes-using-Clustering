# Prediction-of-Students-Career-Outcomes-using-Clustering

Using open data from the Next Generation Life Science (NGLS) Coalition to predict PHD students' outcomes in Excel

## Background
With the data from [the Next Generation Life Science (NGLS) Coalition](http://nglscoalition.org/coalition-data/#close), I applied the cluster analysis to see what is the trend for PHD students' career outcomes from different departments. 

The Next Generation Life Science (NGLS) Coalition contains career outcomes data for PHD students from all departments. There are academia, for-profit, government, other categories.

## Approach
I first translated the data to csv file using tabula. I then calculated the Z value for each career outcomes. The distance is then calculated and the minimum distance is obtained. Finally, I used solver function to find the smallest distance and three clusters.

## Conclusion
The chart below illustrates the three clusters:

![alt text](https://github.com/lshan6/Baltimore-Health-Dept.-Earned-Salaries-Compared-to-their-Tenure-in-Baltimore-City-/blob/master/baltimore%20city.PNG)

It is shown that the majority of cluster #1 went to academia, such as the SOM Cell Biology, A&S Biology, and SOM Neuroscience.
The majority of cluster #2 went to Non-Profit and Government, such as A&S Biophysics, SOM Biomedical Engineering, and SOM Oncology Center.
The majority of cluster #3 went to Academia and for-profit. 

## Takeaway

For future PHD students, it would be beneficial to look at this chart before they choose the department and school. Based on their expected career outcome, they can choose a more suitable department. 
