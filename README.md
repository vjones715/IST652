# IST652
Scripting for Data Analysis
PDF scraping to identify certain codes of Soldiers that indicate when they joined the National Guard. This code is known as ‘B1’ which ties the entry of this code into the Total Army Personnel Database- Guard (TAPDB-G) to the specific the Service Member (SM) entered the Pennsylvania Army National Guard. This information is useful in determining State and National Guard awards owed to the SM. 

Company level leadership do not have access to the database to query this data and are reduced to manually searching through various pages of the SM’s Retirement Points Accounting Management (RPAM) Statement to identify the B1 code and then transposing that date to an Excel file. The RPAM statement is a service log of every duty transaction for an individual SM. The average number of Soldiers per Company in my Battalion is 130. Depending on the length of service for any given SM, the number of pages can extend to 5 or more. The current method is not only time consuming but increases the risk of human error with all the erroneous data within the RPAM statement.

Other digital platforms can be utilized such as the Defense Training Management System that provides the Pay Entry Base Date for all Soldiers; however, this cannot be utilized for Officers as they receive federal commissions and their Basic Active Service Date changes as they become officers. If the officer is prior enlisted, there is no other Open Source access to their Pay Entry Service date. This would require a query from the Battalion Human Resources Section (S1) and will be provided based on priority and current mission. Given the dwindling numbers of full-time staff, this information for State Awards would not be prioritized over Soldier retention efforts and Soldier readiness. 

The output file is the 'Awards.csv'
![image](https://github.com/vjones715/IST652/assets/153471965/94c8d6e8-5bd4-4651-9e3a-9b3129f5916d)
