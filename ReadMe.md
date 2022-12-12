
# Applied Data Analytics

## Wedge Project - Fall 2022 

   ![image](https://user-images.githubusercontent.com/112667258/205748782-db5fc70c-2c92-4b1a-af1b-604385459db7.png)


The Wedge Community Co-Op is a natural foods grocery store located in Minneapolis, Minnesota and the largest co-operative grocery store in the US.  During the course of the semester, our cohort had the opportunity to work with Wedge customer transaction data as a means to improve our analytical skillset and develop better business acumen.  This project is a culmination of those skills, where we break down what we have learned into various tasks. 

 
 
### Task 1: Upload the Files 


`File1 Name`: Wedge 1-Final .ipynb

In Task One, we uploaded transaction records to GBQ from Python (I worked with clean files).  First, I created a path to source the cleaned files (re: clean_files) and assigned to object 'clean_wedge_files,' then uploaded all the data into GBQ data set appropriately named 'wedge.' 



### Task 2: Sample of Owners 

`File2 Name`: Wedge-Part 2-Final.ipynb

In Task Two, we separate owners from non-owners (everyone is welcome at the Wedge!) and take a sample from a list of those owners since this will make it easier to analyze. 




 
	

### Task 3: Building Summary Tables 

`File3 Name`: Wedge-Part 3-Final.ipynb

Finally, for Task Three, we put those analytical skills to the test by building a SQLite database via Python which will contain three tables further diving into transactional data by examining sales by date by hour, sales by owner by year by month, and sales by product description by year by month.



## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - john_results)/john_results)`. 



|  Query  |  Your Results  |  John's Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  | 85923127  |  85760139 | 162,988  |  .002 |
| January 2012 Rows  | 1070907  | 1070907  | 0  |  NA |
| October 2012 Rows  | 1042287  | 1100647  | 58360  | .52  |
| Month with Fewest  | August  | November   | No  | NA  |
| Num Rows in Month with Fewest  |  1025340 | 1025340  | 0  | NA  |
| Month with Most  | April  | April  | Yes  | NA  |
| Num Rows in Month with Most  |  1135000 |  1135000 | 0  | NA  |
| Null_TS: Trans Status | 7123792  |  7123792 | 0  | NA  |
| Null_DT: Datetime | 0  | 0  |  0 |  NA |
| Null_Local  | 235951  |  234843 | 1108  | .005  |
| Null_CN Card Number  | 0  |  0 |  0 | NA  |
| Num 5 on High Volume Cards  | 14987  | 14987  | Yes | NA  |
|  Num Rows for Number 5 | 460630  | 460630   | 0  | NA  |
| Num Rows for 18736  | 12153  | 12153  |  0 |  NA  |
| Product with Most Rows  | Banana Organic  | Banana Organic   | Yes  | NA  |
| Num Rows for that Product  | 614797  |  613142 | 1655  | .0027  |
| Product with Fourth-Most Rows  | Wedge Cookie  | Wedge Cookie  | Yes | NA  |
| Num Rows for that Product  | 405871  | 405060  |  811 | .002  |
| Num Single Record Products  | 2781  | 2795 | 14  |  .005 |
| Year with Highest Portion of Owner Rows  | 2012 | 2012  | Yes  | NA |
| Fraction of Rows from Owners in that Year  | .7451  | .7418  | .0033  | .004  |
| Year with Lowest Portion of Owner Rows  | 2017  | 2017  | Yes  | NA |
| Fraction of Rows from Owners in that Year  | .7513 |  .7513 | 0  | NA |

## Reflections

Overall, I thought this was a good way to 'sum up' what we did this semester and add to our portfolios!  If I were to do it again, I would look at the assignment day one and break down when I would learn each section and attempt it then instead of waiting until the final weeks of class to remember everything we did.  
