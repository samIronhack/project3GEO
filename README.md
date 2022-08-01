# project3GEO

https://www.builtinla.com/2016/10/24/video-game-studios-know

The process 

For the project the Goal is to find the perfect location for our new offices. 
To do this we take into account the requests from our valued employees.  We decided to set our focus on the United States to narrow down our search area. 

After plotting the heat map we determined that the majority of companies are located on the south east of the states in California. After removing all the countries and states that do not match  USA and ‘CA’ and removing the rows that were still lacking long/lat data, address information for their offices. For the ease of the search we dropped all rows that were missing any of these values. After this we were left with 2401 rows of data.

To determine which requirements to take into account for the decision we researched different salary levels of the employees. We used the website glass door to get this information. For each position we took the average income and multiplied it by the total number of employees on this position to get a total spending per employee category. By doing this we ended up with the following dataframe.  The total spending category was then multiplied with the weight factor for each position, the final table creates the order of importance for the location of the office.

We decided on the weight by checking the request the group made and how big the group of employees is. 
Front-end and back-end developers fall under the same group and therefore are above the executives 

The list of requests set by the campany is:

- 30% of the company staff have at least 1 child.
- Everyone in the company is between 25 and 40, give them some place to go party.
- Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design.
- Developers like to be near successful tech startups that have raised at least 1 Million dollars.
- Account managers need to travel a lot.
- Executives like Starbucks A LOT. Ensure there's a Starbucks not too far.
- The CEO is vegan. 
- If you want to make the maintenance guy happy, a basketball stadium must be around 10 Km.


![Screenshot 2022-07-30 at 18 01 47](https://user-images.githubusercontent.com/104360125/181925263-770a23de-ff8d-45bd-8ca1-44d41afcc97b.png)

![Title Salary Count Total salary](https://user-images.githubusercontent.com/104360125/181925286-09e59fe8-9963-4cee-99dd-b57202d3108a.png)

![Screenshot 2022-07-30 at 18 02 40](https://user-images.githubusercontent.com/104360125/181925304-586ca9ea-bc51-4c6c-85b1-7617fb10fd28.png)

![Screenshot 2022-07-30 at 18 02 58](https://user-images.githubusercontent.com/104360125/181925317-020f80b9-ddcf-42ac-b3ae-b5d05bc9538f.png)



While creating the final read me we realised that we forgot to implement one of the requests because on Friday we understood we only had to look at tech companies which is all the companies in the database. The ranking of front end and back end developers was therefore ignored. 


To further reduce the number of possible locations for the office in LA we created a function that will keep eliminating offices that do not meet the requests made by the company. 

After applying all the filters we ended up with four possible locations. 

- sdfgsdfgsfdag
- Sferen de
- Suf suf
- Suf ds

All the locations are showcased in the following visualisations 


Img 1 

Img 2 

Img3 

Img4 


We have requested comments from a person with authority to make a final decision on what office we should pick in LA and he recommended us to go with.


We did not trust this advice however and had a closer look at the data from the maps we have shown you before. We went by the order of importance per request and checked which had more options. From this we were able to conclude that the office on…. Was the best option for our offices. 














