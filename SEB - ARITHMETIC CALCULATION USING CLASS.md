# Exp.No:4e
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a python program to perform addition and multiplication operation using class and if..elif statement

note:
class name should be calc, function name should be setvalues( to set a and b values) ,add and mul
cases : 
* choice 1 ->perform addition ,
* choice 2-> perform multiplication ,
* choice 0 -> exiting, other choices -> print 'invalid choice'

---

### ALGORITHM

1. Begin the program.
2. Define the Class Calc:
   * Initialize the class with an __init__ method (optional, but good practice).
   * Define a method set_values(a, b):
      * Accept two parameters, a and b.
      * Store these values as instance attributes (e.g., self.a and self.b).
   * Define a method add():
      * Calculate the sum of self.a and self.b.
      * Return the calculated sum.
   * Define a method mul():
      * Calculate the product of self.a and self.b.
      * Return the calculated product.
4. Main Program Logic:
    * Create an instance of the Calc class (e.g., my_calc = Calc()).
    * Prompt the user to input two numbers for a and b.
    * Call my_calc.set_values(a, b) to store the numbers.
    * Start an infinite loop to present the menu and accept choices.
    * Inside the loop, display the menu options: 1 for Add, 2 for Multiply, 0 for Exit.
    * Read the user's choice.
    * Use if/elif/else to handle the choice:
       * If choice is 1: Call my_calc.add(), store the result, and print it with a descriptive message.
       * Elif choice is 2: Call my_calc.mul(), store the result, and print it with a descriptive message.
       * Elif choice is 0: Print an exiting message and use break to exit the loop and terminate the program.
       * Else (any other choice): Print the message 'Invalid choice'.
5. Terminate the program.

---

### PROGRAM

```python
class calc():
    def setvalues(self,a,b):
        self.a = a
        self.b = b
        
    def add(self):
        self.a + self.b
        
    def mul(self):
        self.a // self.b
        
a = int(input())
b = int(input())

obj=a+b
obc=a*b
choice = 1

while choice!=0:
    choice = int(input())
    if choice ==1:
        print("Result: ",obj)
        
    elif choice == 2:
        print("Result: ",obc)
        
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")


print()
```

### OUTPUT
<img width="1185" height="381" alt="image" src="https://github.com/user-attachments/assets/aaf81214-65c1-449d-a16d-b397d557b7ad" />

### RESULT
Therefore, the output is the example to write a python program to perform addition and multiplication operation using class and if..elif statement
note:
class name should be calc, function name should be setvalues( to set a and b values) ,add and mul
cases : choice 1 ->perform addition ,choice 2-> perform multiplication ,  choice 0 -> exiting, other choices -> print 'invalid choice'
