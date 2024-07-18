# Factory Design Pattern for Board Game Creation

## Problem Statement

You are building a gaming application where different types of board games (e.g., Tic Tac Toe, Chess, Snake & Ladder) need to be created dynamically based on user input. Implement the Factory design pattern to facilitate the creation of these game objects without explicitly specifying their classes, ensuring flexibility for future game types.

## Task 1 - Creating a Common Parent Class - BoardGame

To streamline the creation of board games, implement the `BoardGame` class as a common parent class. This class should define attributes and methods that are common to all types of board games. An abstract method `gameType` has been provided as an example, which needs to be implemented in specific game classes.

## Task 2 - Implementing the Factory Pattern

Implement the `BoardGameFactory` class that follows the Simple Factory pattern. This class should provide a method to create different types of board games based on the `GameType` and other parameters passed to it. This approach abstracts the instantiation logic away from the client code, making it easy to add new board game types in the future.

### Instructions

1. **Implement the `BoardGame` class:**
   - Define attributes and common methods that all board games share.
   - Ensure the class structure supports future extensions for different board game types.

2. **Implement the `BoardGameFactory` class:**
   - Implement a method to create board game objects based on the `GameType` and other necessary parameters.
   - Ensure the factory class can instantiate different board game types dynamically.
