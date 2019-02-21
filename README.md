# Roulette Wheel coding exercise

You should write the appropriate classes and tests in the RouletteWheel.Core and RouletteWheel.Tests.NUnit projects accordingly, to model and test the following roulette wheel.

We are interested in the unit tests that model and prove the requirements, and no user-interface is required
All tests should execute against the same roulette wheel code

You must use interfaces and adhere to SOLID principles 

Marks awarded for:
* Demonstrable TDD
* Appropriate Design Pattern (GoF, etc.)
* Naming conventions

Time alloted is 1-1.5 hours

In each case:
The amount of money is called the [stake], the number/range/colour is called the [guess]

## Scenario 1
* The user should be able to place a bet of £50 on a number between 0 and 32 and spin the wheel
* A random number between 0 and 32 is generated. 
* If this number matches the user's [guess] then they win the stake * 10

## Scenario 2
* The user should be able to place a bet of £50 on the number 0 and spin the wheel
* A random number between 0 and 32 is generated. 
* If this number matches the user's [guess] then they win the stake * 20

## Scenario 3
* The user should be able to place a bet of £50 on any of the following ranges, and spin the wheel
1-10
11-20
21-25
26-32
* A random number between 0 and 32 is generated. 
* If this number falls within the range the user entered, then they win the stake * 2.5

## Scenario 4
* The user should be able to place a bet of £50 on either Odd or Even, and spin the wheel
* A random number between 0 and 32 is generated. 
* If this number is odd and the user's guess was Odd, then they recieve the stake * 1.5
* If this number is Even and the user's guess was Even, then they recieve the stake * 1.5

## Scenario 5
* The user should be able to place a bet of £50 on either Red or Black, and spin the wheel
* A random number between 0 and 32 is generated.
* The number is considered Green if 0, and Red if in the following list [1,3,5,7,9,11,13,15,17,21,23,25,27,29,31], otherwise it is black
* If this number is Red and the user's guess was Red, then they recieve the stake * 2
* If this number is Black and the user's guess was Black, then they recieve the stake * 2

