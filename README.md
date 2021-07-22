# coffee_machine
Very simple yet effective coffee machine simulator able to accept quarters, dimes, nickels, and pennies.

If the client doesn't have enough money, it prompts another client again.

In case the coffee machine doesn't have enough supplies, i.e., milk, client has only limited choices.

## Commands
`report` Prints current state of machine's water, milk, coffee, and money.

`off` Turns the coffee machine off.

`latte` Serves the client with a latte, returns them change and deducts milk, coffee, and water from the machine's current state. Adds money to machine's current state.

`espresso` Serves the client with a espresso, returns them change and deducts coffee, and water from the machine's current state. Adds money to machine's current state.

`cappuccino` Serves the client with a cappuccino, returns them change and deducts milk, coffee, and water from the machine's current state. Adds money to machine's current state.

## Usage

* First, clone the repo:
```
git clone https://github.com/mclbdn/coffee_machine
```
* In terminal type:
```
python main.py
```

![Photo of Terminal running coffee machine app.](https://raw.githubusercontent.com/mclbdn/coffee_machine/main/coffee_machine_screenshot.png)
