# python-challenge-1
### Files to Refer to:
#### [menu.py](menu.py)
#### [menu.ipynb](menu.ipynb)
* executes without any error in jupyter notebook

### Instructions
* Download the file [menu.ipynb](menu.ipynb) and open in jupyter notebook to execute the code.  OR
* Open the [menu.py](menu.py).py in VS Code, but its throwining an error match statement.

### Background
Designing an interactive ordering system from a food truck menu 

### About Challenge
* menu{} - dictionary with multiple dictionaries in inside.
is created 
* Order_list[] - is an empty list which will store customer's order  
* menu_list{} - is a dictionary to store the menu from which customer will place an order which will be stord in order_list[] with item name, price and quantity.
    * During menu category selection from menu{} to print out the keys, there are checks made to validate if selected option exists in the menu or not using for and if statements.

    * If customer does not select a valid option, an error message is displayed which loops back to the show menu catgory else it will display the menu_list {} based on category selection.

    * after every selection, customer is prompted to continue ordering or no and customer's response is matched using match case statement.
    
    * If customer continue to order, they will be prompted to make selection else it will thank and prints the items selected as confirmation.

    * Space strings are calculated on keys in order_list[] are calcuated and used to print the order receipt for proper formatting 

    * A comprehension list is used to calcuate the total price of items in order_list by price and quantity.
    


    










