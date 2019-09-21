# **Enscapsulation-** _**Problem03:Validation of Data**_
## **Problem 03**
### _**Validation of Data**_
> _**NOTE:**_ Creating a public **Startup** class with the namescape **PersonInfo**.  

Expand _**Person**_ with proper validation for every field:
* Names must be at least 3 symbols
* Age must not be zero or negative.
* Salary cannot be less than 460.0  

Print proper messages to the user:
* "Age cannot be zero or a negative integer!"
* "First name cannot contain fewer tha 3 symbols!"
* "Last name cannot contain fewer than 3 symbols!"
* "Salary cannot be less than 460 leva!"
> Use Argument Exception to show the message that mentioned before.

## **Input and Output**
**Input** | **Output**
----------|-----------
5 | Age cannot be zero or a negative integer!
Asen Ivanov -6 2200 | First name cannot contain fewer than 3 symbols!  
B Borisov 57 3333 | Last name cannot contain fewer than 3 symbols!
Ventsislav Ivanov 27 600 | Salary cannot be less than 460 leval!
Asen H 44 666.66 | Ventsislav Ivanov gets 660.00 leva.
Boiko Agelov 35 300 |

## **Solution**
1. Using the _**Person**_ class which created in the previous tasks.
2. Adding validation to all the setters in _**Person**_ class. In the validation process, we used _**Creating and Throwing Excaptions**_ to indicate that error has occurred while running the program. Exception objects that describe an error are created and then thrown with the throw keyword. The runtime then searches for the most compatible exception handler.
   ![Imgur](https://i.imgur.com/oKeeCAe.png)  
   ![Imgur](https://i.imgur.com/xUBNdjy.png)  
   ![Imgur](https://i.imgur.com/Utdg1Cf.png)
   ![Imgur](https://i.imgur.com/upqKd4r.png)  

3. In _**Program**_ class, we using _** try and catch**_ to find the exception and handler that just display the message in the screen.When the throw statement is called from inside _**Person class**_, the system looks for the catch statement and displays the message Exception caught.  
  ![Imgur](https://i.imgur.com/vQjqvGt.png)

## **The result**
![Imgur](https://i.imgur.com/sQSEuvT.png)
