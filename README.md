# pandas-challenge
UCI Bootcamp - Challenge 4 with Pandas

Analyzed the PyCitySchool data set to see if there is any relationships between school size, budget, and types with student success rates. 

The data set consists of high school data with information about both the school and students. 
Characteristics of schools were kept track of through the following columns: 
- school_name: Name of the school
- type: Type of school (Charter or District)
- School ID
- budget: the school's total budget (not budget per student)
- size: amount of students in the school

Student data included:
- Student ID
- student_name 
- gender           
- grade            
- reading_score     
- math_score        

The school's student success rate is measured by taking the average of the number of students who passed both reading and math divided by the total students in the school. Students who received a 70% or higher is considered as passing.

The Pandas library was used to:
- create dataframes
- filter and group data
- calculate aggregated values such as the average, count, and sum of school data
- organize the data into specific categories/ranges through bins


As a results of the analysis, the data showed that school budget and size did not have much relations to student success. It was found, that school type had a relationship to success. Charter schools were found to have higher percentages of students passing both math and reading even if the school had low student enrollment and smaller budgets. District schools were found to have lower pass rates even with higher budgets and student size.
