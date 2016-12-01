# HDP_Test_Q2
Output data of hadoop test question 2


Q2:
Find out Salary trends between Male and Female employees during each decade in every department. The output should be in the following format: Department, Decade, Gender, avg_salary. Please upload the final CSV along with the code and jar files(if any) to your github and provide the link below.


To get this done we have performed one query which get the Department name, Decae , Gender and Average salary.

In this question we have First get the All Department types.
Then the term "Decade" indicates that 10 years of span, for this I have checked the all department data and employess from, to date data and as analysis found that we have data available from 1985.
Here we have created decades in below format :


 1. 1981 to 1990
 2.1991 to 2000
 3.2001 to 2010
 4.2011 to 2020
 
 Then jumped to next required data as department wise, each decade wise  and then gender wise.
 
 Here in available data we have Gender Male (M) and Female (F).
 
 so as get the data to process as 
 
 Each depatment then 4 derived decades  for Gender M and Gender F.
 
 For now submited only one departments with 2 decades with gender M and F as 4 files using the script.
 
 Now to get the remaning departments-decades-gender wise file need to chnage the values in script.
 
 due to in-suffecient space on created hadoop machine Not able to process this large number of all departmnets data, but bty changing values in given script will get the reqired otput files.
 
 
