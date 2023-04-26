# Coffee-machine-in-python-with-oop
coffee vending machine with python


This code block creates a coffee machine application. In the code, an object menu is created from the Menu class using menu.py. The get_items() method of the Menu class is used to display the drinks that the user can choose from. The user makes a choice which is stored in the choice variable.

The if condition checks if the user has selected the off option. If so, the is_on variable is set to False and the loop is exited. If the user chooses the report option, objects created from the CoffeeMaker and MoneyMachine classes call the report() method to report on the resources and money status.

If the user selects a drink, the find_drink() method of the Menu class is used to get the selected drink object, and the is_resource_sufficient() method of the CoffeeMaker object is used to check if there are enough resources. If there are enough resources, the make_payment() method of the MoneyMachine class is called with the price of the drink, and the payment is made. Finally, the make_coffee() method of the CoffeeMaker object is called to prepare the drink and serve it to the user.
