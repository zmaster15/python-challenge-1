# python-challenge-1

**Food Truck Menu Code**

## Table of Contents
* [Introduction](#introduction)
* [Installation Requirements](#requirements)
* [Usage](#usage)
* [License](#license)
* [Acknowledgement / Contributing](#acknowledgementcontributing)

## Introduction
This project is the first coding module challenge that we had to complete as part of the Denver University AI Bootcamp coursework. 

The code 'menu.py' is a simple 2 level food ordering system that allows the user to select from a main (top level category) selection of food/drink items and then make a selection from within that category. The user is requested to specify the item of interest under the main category and requested to enter the quantity\* that they would like to purchase. 

The user can continue to order multiple items from the menu, and once they are satisfied, they will be presented with the full list of items ordered, the running total + 8% sales tax that is applied. 

\*NOTE: If user enters an invalid character (ie. not an integer) for quantity, the quantity is updated to a default value of 1. 

## Installation Requirements
*Requirements*: You must run Python 3.12.7 to execute the code as the code uses match case sytax that is older versions of python will not recognize.

## Usage
Aspiring food-entreprenuer can freely use this code to run their ordering system with a simple modification of the dictionary at the top of the code. Adding/ removing of food items should be tested at the end of every edit to ensure that the code can still execute. A test print statement has been added at line 151 that can be uncommented to enable testing of orders correctly making it into the 'orders_list'. 

## License
I've included the MIT License to encourage collaboration and use by the community.

## Acknowledgement / Contributing
Thank to the guidance of the Denver University AI Bootcamp Teachers Assistant's and their hints via comments that helped me complete this assignment. Without this I would've been completely lost. 

While a section of this code was written by the Denver University AI Bootcamp Teachers Assistant, it has been modified / completed by me. 

