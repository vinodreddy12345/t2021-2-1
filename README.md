# t2021-2-1

# Problem 1: Create a small calculator
# step1: we create a calculator class and define function that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.
# step2: we create a object that takes two input numbers 'a' and 'b' and the type of operation as a string.
# step3: below i have created a calculator object that takes 2 inputs and and using dot notation i have called functions  such as addition, subtraction, and multipilication to perform action
#                calculator = Calculator(a, b)
#                result = calculator.add()  
#                result = calculator.subtract()  
#                result = calculator.multiply()  
#                result = calculator.divide() 



# Problem 2: Generate a series of numbers
# step1: Here we have defined function that takes one paramater "a"
# We initialize an empty list called result to store the series of numbers.
# We iterate from 1 to using for loop.
# Inside the loop, we check if the current number i is odd by using the condition i % 2 != 0.
# If i is odd, we append it to the result list.
# last we return the result list.

# Problem 3: Generate a series of numbers with a variation
# The code structure is the same as in Problem 2.
# After the for loop, we add an additional condition to check if a is even (a % 2 == 0).
# If a is even, we remove the last element from the result list using the pop() method.
# and last we return the result list.

# Problem 4: Count multiples of numbers
# we define a function count_multiples that takes a list of numbers as input and counts the multiples of each number from 1 to 9
# We initialize a dictionary called counts with keys ranging from 1 to 9, and all values set to 0.
# We iterate over each number in the numbers list using a for loop.
# Inside the loop, we iterate over each divisor in the keys of the counts dictionary.
# For each number, if it is divisible by a divisor, we increment the count for that divisor in the counts dictionary.
# last we return the counts dictionary.
