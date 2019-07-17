# ***Python Analysis on city schools***

 

### **Objective :**

This was an analysis on how high school students perform in reading and math in a fake school district.   Did charter schools do better in standardized test than public schools? Did schools with high budget outperform schools with a lower budget ?  Did smaller schools provide a better education than larger ones?

 

### **Author :**

Emily Mo

 

### **About the data :**

Two sets of data were provided -  school data containing all 15 high schools in a school district and score data by student and by high school.

The data was merged to provide :

-  school name

- school type - charter school or public school

- total number of students

- total school budget

- budget per student

- average math score

- average reading score

- % passing math

- % passing reading

- overall passing rate (average of reading and math)

  

### **About the python script :**

The python script uses :

- jupyter notebook,

- numpy,

- csv file processing, 

- pandas dataframes - mean(), len(), format, map, set_index(), groupby, count(), iloc, sort_values()

- pandas merge,

- and pandas bin and cut.   

    

And the results showed :

- Total budget, budget per student, average math score, average reading score, school type, percentage of students passed math, percentage of students passed reading, the overall passing rate by school,
- The average scores of math and reading by school by grade, 
- top performing schools (by passing rate),
- bottom performing schools (by passing rate),
- charter schools performed better than public schools,
- lower budget schools outperformed high budget ones,
- small schools (less than 1000 students) and medium schools (less than 2000) received better scores than larger schools.



### Deployment

The python script, PyCitySchools.ipynb can be run in jupyter notebook.

