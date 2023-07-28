# Refactoring test in C#

## Description

You are asked to refactor the UserService class and, more specifically, its AddUser method. 
Assume that the code is sound in terms of business logic and only focuses on applying clean code principles. Keep in mind acronyms such as SOLID, KISS, DRY and YAGNI.

## Limitations
The Program.cs class in the LegacyApp.Consumer shall NOT CHANGE AT ALL. This includes using statements. Assume that this codebase is part of a greater system, and any non-backward compatible change will break the system.

You can change anything in the LegacyApp project except for the UserDataAccess class and its AddUser method. Both the class and the method NEED to stay static.