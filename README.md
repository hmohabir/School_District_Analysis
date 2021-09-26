# Overview of the School_District_Analysis
Analysis performed with the usage of school and student data to make informed decisions to the school district with regards to performance, grades, budget and proprieties.

## Challenge
It was discovered that the 9th grade scores at Thomas High School was incorrect. As such, it was best to replace these grades only with an NaN – not-a-number. All other associated data was kept the same. This change did not significantly alter the resulting report.

##Result
### School District Summary
When assessing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped .1, the average reading score stayed the same, the percentage passing math dropped 1%, the percentage passing reading dropped 1%, and the overall passing percent dropped 1%.

![School Districy Summary](https://github.com/hmohabir/School_District_Analysis/blob/main/School%20District%20Summary.png)

### School Summary
Even with the absence of the 9th grade scored for Thomas High School, the overall grades were not significantly affected.

![School Summary](https://github.com/hmohabir/School_District_Analysis/blob/main/School%20Summary.png)

Thomas HighSchool was not in the top five highest performing or the bottom five performing schools:

![Top five performing schools](https://github.com/hmohabir/School_District_Analysis/blob/main/Top%20Five%20Performing%20Schools.png)

![Bottom five performing schools](https://github.com/hmohabir/School_District_Analysis/blob/main/Bottom%20Five%20Performing%20Schools.png)

Per the school summary, the score replacements for Thomas High School 9th grade did not significantly affect the school’s ranking. Its 19th, 11th and 12th grade actually ranked second best when compared to the other high schools of the same grades. The good news is it did not rank among the bottom five performing schools either. Per school summary, it ranked 8th among the 15 high schools.

### Average Math Scores by Grade & School

A good note to be made is that the 9th grade data replacement for Thomas High school did not change the overall math and reading scored by grade. The table above shows that the data remained intact for the other grades 

![Average Math by Grade by School](https://github.com/hmohabir/School_District_Analysis/blob/main/Average%20Math%20by%20Grade.png)

![Average Reading by Grade by School](https://github.com/hmohabir/School_District_Analysis/blob/main/Average%20Reading%20by%20Grade.png)


## Summary


### School Spending summary

There is no direct correlation between higher spending and higher overall passing. In fact, the best performers possessed the lower spending per student. 
According to the summary above, the lowest spending yielded the best %passing and the highest spending yielded the lowest %passing

![School Spending Summary](https://github.com/hmohabir/School_District_Analysis/blob/main/School%20Spending%20Summary.png)

### School Size Summary

When reviewing the School Size summary, removing the 9th grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing). The best performing schools are the small ones

![School Size Summary](https://github.com/hmohabir/School_District_Analysis/blob/main/School%20Size%20Summary.png)

### School Type Summary

In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.

![School Type Summary](https://github.com/hmohabir/School_District_Analysis/blob/main/School%20Type%20Summary.png)


### 
