# Four Pillars of OOP

## Part 1 Class

### Represent Employee - Class

1. Create an Employee class
2. **Attributes:** name, age, salary, location
3. **Behavior:** raiseSalary (can have parameter or not)

**Things to consider**: Static or Non-Static Members?

4. Create a main class for building Employee instances
5. Build two Employee instances
6. Give one Employee a raise
7. Display the salaries of both Employees

[**Implementation Represent Employee - Class**](https://replit.com/@msoro/employee-class-challenge1#src/Main.java)

## Part 2 Encapsulation

## Bank Account - Encapsulation

1. Create Bank Account Class
2. **Attributes:** owner, balance
3. **Behavior:** withdraw, deposit, getter(owner or balance), setter
4. Create constructor
5. Test Bank Account Class
6. Create a Main class that makes a Bank Account instance
7. Withdraw a certain amount using the withdraw method
8. Print out the resulting balance

**Note:** The Bank Account attributes should not be directly accessible

[**Implementation Bank Account - Encapsulation**](https://replit.com/@msoro/banking-application-encapsulation-challenge2#src/Main.java)

## Part 3 Inheritance

[Inheritance Person TO Employee TO Analyst AND Salesperson](https://replit.com/@msoro/Person-Employee-Analyst-Salesperson-Inheritance#src/Main.java)

## Reduce Redundant Code with Inheritance

1. Create a **ModArrayList** class
2. Add a **getUsingMod** method that takes in an index and retrieves an item from the list at that index
3. If the index is invalid, then the mod and absolute value operations should be used to make the index positive and mod the index based on the length of the list. If the index is negative turn it to positive.
4. ModArrayList should have all the functionality of **ArrayList**
5. Additional **getUsingMod**

[Implementation Reduce Redundancy using Inheritance](https://replit.com/@msoro/Reduce-Redundancy-Inheritance#src/Main.java)

## Part 4 Polymorphism

### Runtime Polymorphism

**Method Overriding**

[Polymorphism OddArrayList Extends ArrayList Class](https://replit.com/@msoro/Polymorphism-OddArrayList-Extends-ArrayList-Class#src/Main.java)

[Polymorphism ConditionArrayList Extends ArrayList Class](https://replit.com/@msoro/Polymorphism-ConditionArrayList-Extends-ArrayList-Class#src/Main.java)

### Compile-time Polymorphism

**Method Overloading**

- Multiple ways to create and manipulate an object with different sets of inputs we can use method overloading.
- Java decides what method to use based on the input't type and the number of parameters used at compile time, hence compile time polymorphism.

[Polymorphism Compile-Time ConditionArrayList Extends ArrayList Class](https://replit.com/@msoro/Polymorphism-Compile-Time-ConditionArrayList-Extends-ArrayList-Class#src/Main.java)

## Adding Phone Contacts

1. You want to add a series of contacts to your phone
2. There are different levels of information about each contact some will have just name and phone number, others would have email.
3. Consider name, phone number and email
4. Create a program that allows you to create contacts with different levels of information.
5. After creating a contact instance, print it in the console.

[Polymorphism Contacts Challenge 4](https://replit.com/@msoro/Polymorphism-Contacts-Challenge4#src/Main.java)
