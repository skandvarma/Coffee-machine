# Coffee-machine
Coffee machine program using python
This code simulates a coffee machine that offers different types of coffee drinks. It maintains a menu with drink options, their ingredients, and costs. Users can choose drinks, insert coins to make payments, and receive coffee while deducting resources.

Key Components:

MENU: A dictionary defining available drinks, their ingredients, and costs.
profit: Tracks the total earnings from coffee sales.
resources: Tracks available water, milk, and coffee for making drinks.
Functions:
is_resource_sufficient: Checks if there are enough resources to fulfill an order.
process_coins: Calculates the total value of inserted coins.
is_transaction_successful: Verifies if the payment is sufficient and handles change.
make_coffee: Updates resource quantities based on the ordered drink.
Main Loop:
Repeatedly asks the user for their drink choice.
If the choice is "off," it ends the simulation. If "report," it displays available resources and profit.
If a valid drink choice is made, it checks resources, processes payment, and serves coffee.
The code has been refined to ensure that the "Here is your {drink}" message is printed only once after a successful transaction. It provides a more organized and user-friendly experience for simulating a coffee machine.
