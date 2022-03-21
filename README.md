# School_District_Analysis.
Learning to use Pandas and Jupiter Notebook
<h1>Project Overview</h1>
We have been asked to review the test scores for both math and reading for a school district and compairing those scores to the schools budget. Then breaking down the data further to specifiy if the school if a public or charter school. 

While in the process of filtering out the data, decrepencies were found for a specific school and grade. This finding added some complexity to the code, requiring us to exclude data from the final results to not scew the outcomes. 

<h1>Resources</h1>
- Data Sources: schools_complete.csv , students_complete.csv
- Software: Python 3.9, Visual Studio Code, 1.64.2 (Universal), jupyter notebook

<h1>Summary</h1>
<h4>The analysis of the school district shows that:</h4>

-There were "39170" students scores provided from the origional data scource.
-We removed "461" students scores due to potential errors in the origioanl data set.
-The schools as a whole have a total budget is $24,649,428.00

and much more 

<h4>How is the district summary affected:</h4>
The district overall passing was very minorly effected by the changes made in the data .


<h4>How is the school summary affected?:</h4>
Thomas high schools passing percentage was 90.948012 and it was changed to 90.630324 when we removed the 9th grade data.


<h4>How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?:</h4>
Removing the scores for Thomas High School's has effected the overall passing percentage in the medium ($630 - $644) pending range by lowering it less than 1%.


<h4> These images show specifics of how does replacing the ninth-grade scores affected the scores:</h4>

<img width="995" alt="Overall averages before removal" src="https://user-images.githubusercontent.com/69826496/159367264-6d7e907b-2df5-46e9-a8b4-8d5380532f0b.png">

<img width="715" alt="Overall Averages after removal" src="https://user-images.githubusercontent.com/69826496/159367288-48b484a7-d5b9-4535-ad0b-b4de7f4e29ca.png">


<h1>Challange Summary</h1>
As you can see we have pulled together the analysis of the school district grades; made changes to what information we take into account; and provided clear numbers on that include a before and after the updated to the Thomas High School data. 
<br>
With the many steps, DataFrames, and print outs that show the progression of the code over time you can see clearly the change that are made. You can also see clearly where you can go in and make changes without having to re-do the whole process. Again we are working with a tool that allows you to use this code to break down future CSV files and potentially make minor changes. 
<p>
