# Smart-traffic-system-polymorphism-

## Project Overview
This repository contains a solution for the **Smart Traffic Management System** case study. The project demonstrates Object-Oriented Programming (OOP) concepts, specifically **Polymorphism** and **Inheritance** in Python.

## Task Requirements
* **Parent Class:** `TrafficDevice`
* **Child Classes:** `TrafficLight`, `SpeedCamera`, `PedestrianSignal`, and `EmergencySiren`.
* **Polymorphic Behaviour:** Each child class overrides the `activate()` method to perform its specific function.
* **Type-Agnostic Execution:** Devices are stored in a list and activated within a single loop without checking their individual types.
* **Extensibility:** Demonstrates how new classes (such as `EmergencySiren`) can be added and executed seamlessly without altering the core activation logic.

## How to Run
1. Ensure Python 3.x is installed on your machine.
2. Clone the repository.
