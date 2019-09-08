### Instructions

Create a new IPython Notebook, and use it to answer the following questions. 

#### Question 1 

Assume that you are responsible for counting the results of a survey asking participants whether they would like to go on a class trip.  You receive the results of the survey in the form of string.  A yes vote could be either “Y” or “y” and a no could be either “N” or “n”.  The list votes has the values. 
 
You can copy and paste the following to have the values initialized.
votes = "y y n N Y Y n n N y Y n Y"

Use python to determine the percentage of yes and no votes in this small dataset.  
Note:  There is no need for a “for” loop: by simply exploring the methods available on any string, you will find enough tools to do this.
 Make sure that you show all your code and make sure that you are not manually inserting the number of yes and no votes into the percentage calculation.  Your code should automatically count the results and then calculate a percentage.  This means that if you changed the votes string your code would still work

#### Question 2 

Steven keeps a list of the people that he knows in several dictionaries.  You can define these dictionaries using the following code snippet.  
family = {'Jay': '123 Liverpool', 'Lisa': '567 Anfield'}
friends = dict(Michael='455 Newcastle', Didi='321 Munich')
colleagues = dict([('Luis','899 Barcelona'), ('Philippe', '332 Brazil')])

Write code that will do the following:
1.	 Print out the names of all of Steven’s friends.
2.	Now print all of their addresses.
3.	Now print them as “pairs” (name, address).
4.	Michael seems to have betrayed Steven.  Remove him from the friends list.
5.	Steven needs to mail everyone for a party.  Make a single dictionary containing everyone.
6.	Steven is visiting Barcelona and wants to visit Luis while he’s there.  Get his address.
7.	Steven has moved to the USA and would like to cut all ties with everyone.  Remove everyone from the dictionary.   

#### Question 3

Create a Python list with the following values: [10, 25, 45, 101, 121, 135, 1244]

•	Print the third element (45) of the list. [recall, the first element is in cell 0]
•	Compute the sum of the values. 
•	Compute the mean of the values. [len() gives the number of elements in a list]     
•	Compute the product of all the numbers (multiply them all together). 


#### Question 4 

FizzBuzz is a classic programming exercise. Iterate over the numbers from 0 to 99 and for each number:

•	If the number is divisible only by 3, print Fizz, and add the number to a list (all numbers from this step should be stored in the same list).
•	If the number is divisible only by 5, print Buzz, and add the number to a list (all numbers from this step should be stored in the same list).
•	If the number is divisible by both 3 and 5, print Fizz Buzz, and add the number to a list (all numbers from this step should be stored in the same list).
•	Finally, print all the three lists

No number should appear in more than one list!! For instance, 15 should be in the list where the number is divisible by both 3 and 5.

Hint1: The modulo operator which gives you a remainder is the percentage sign, %. For example:

In [1]: 5 % 2

Out [1]: 1

Hint2: Create three empty lists. To assign a certain number to a list, you can use the append() function, e.g., “listname.append(number)”.

