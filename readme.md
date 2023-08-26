# Coffee Machine Application

## **[100 Days of Code: The Complete Python Pro Bootcamp for 2023](https://www.udemy.com/course/100-days-of-code/)**

By Dr. Angela Yu

*Days 15, 16 of 100:* Local Environment Setup & Object Oriented Programming

## Project Specs

Using the Python console and an input interface, create a coffee machine that makes three different types of coffee drink: latte, espresso, and cappuccino; takes payment for each item, returns change if necessary; and updates the ingredients resources amounts.

This application is written with Python 3.11.

![alt text](https://github-readme.s3.us-west-1.amazonaws.com/coffee-machine.png)

### Main Features
 
A manager is also able to print a report of all of the current ingredient resources available: water, milk, and coffee, as well as how much money has been made:

![alt text](https://github-readme.s3.us-west-1.amazonaws.com/coffee-machine-report.png)

## Usage & Requirements

This project has three classes:
- Menu
- MoneyMachine
- CoffeeMaker

## Workflow
In the Python console, a user is asked what they would like and are then presented with three options: `latte/espresso/cappuccino`

### Menu Selection
Once the user makes a selection by typing in one of the menu items into the input, the app checks the available resources to see if there are enough ingredients to make the drink. If so, the app moves to the payment section.

### Payment
During payment, the app presents the user with the cost of the drink and then asks the user to deposit coins to pay for the beverage, prompting the user to enter how many of each coin they are depositing:
- How many quarters?
- How many dimes?
- How many nickles?
- How many pennies?

If sufficient coins were not deposited, the app states `Sorry that's not enough money. Money refunded.` and then resets.

If there is change, the app states `Here is $0.0 in change.` 

### Transaction Completion
If there are enough ingredient resources and the user deposited enough money, the app presents the user with their selected drink with an emoji and bids them to enjoy.

The app then resets to the `What would you like?` input.

### Manager Functions

There are two key-words that a manager can enter into the prompt input to manage the machine:
- off
- report

Entering the word `off` stops the machine from asking for new menu selections. 

Entering the word `report` prints out a detailed report of ingredient resources and money collected:
```
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5
```

# Getting Started

All of the commands below should be typed into the Python terminal of your IDE (I use PyCharm for my Python Development).

First, clone the repository from Github and switch to the new directory:

    $ git clone git@github.com:shelbyblanton/coffee-machine.git
    
Then open the project in PyCharm.
    
There are no libraries to load for this project.

**Setup is complete!** 

Click Run in PyCharm to see the app in action.


# Author & Credits

Programmed by **[M. Shelby Blanton](https://www.linkedin.com/in/shelbyblanton/)** under the instructional guidance of **[Dr. Angela Yu](https://www.udemy.com/user/4b4368a3-b5c8-4529-aa65-2056ec31f37e/)** via **[Udemy.com](udemy.com)**.
