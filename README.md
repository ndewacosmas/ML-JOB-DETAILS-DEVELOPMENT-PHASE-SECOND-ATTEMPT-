# ML-JOB-DETAILS-DEVELOPMENT-PHASE-SECOND-ATTEMPT-
MACHINE LEARNING JOB DETAIL-DEVELOPMENT PHASE SECOND ATTEMPT 


ML-JOB-DETAILS
MACHINE LEARNING JOB DETAILS

The purpose of this area is to make analysis of the data which are collected or extracted from the result of ETL work by conducting each categories of the data and making analysis for example of doing the analysis of the student in group A, group B, Group C and other groups.

This Machine learning under this project will anable to show number of student from Some high school and students who scores in to Different subjects According this project the machine learning it facilitate how the data are extracted from source and transformed and loaded into yhe Processing stages due to the use of Mschine learning it help to show the range of score of the Maths,Reading and writting of the students who are attending the examination as shown below.



![analysis of ML NEW](https://github.com/user-attachments/assets/3fc70912-897a-4a5f-a853-65bcea61dfc0)


Source: StudentsPerformance.csv 

according this project the marks of the student which are scored in math it ranges from 0 to 100, and Reading score it ranges from 17 to 100 and writting scores it range from 10 t0 100.

This analysis it show that the most of the student scores it range on 60-70 in maths, in reading it range of 66.80 -75.10 and writing score ranges to 73-82 marks
Due to this project author Identify that the Machine Learning (ML) work will start after the completion of the ETL is completed, the data which are extracted from the source will be proved after checking status table.


![full view1](https://github.com/user-attachments/assets/a5f113f0-a675-4774-92e2-6ab992e6e5cd)
Source: StudentsPerformance.csv 

The work schedule depends on the student performance it is Test mode or production Mode

. Test Mode = Job runs every 1 minutes

. Production Mode = Jub Runs every quarter

Theproposed mode of the project can be changed according the Execution_Mode Items under ML in the Docker - Compose.yaml file.

Test Mode :
environment:


   -EXECUTION_MODE = test

   Production Mode:

   environment:

         -EXECUTION_MODE = Production
