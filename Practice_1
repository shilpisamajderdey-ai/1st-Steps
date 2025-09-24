## IF Else Statement ## 

age= int(input("How old are you?" ))

def age_1(name):
    if age >= 18:
        print("You are an adult.")
    elif age> 100:
        print("Age seems unrealistic.")
    elif age< 0:
        print("Age cannot be negative.")
    else:
        print("You are a minor.")
    print("Thank you for using our program!")

age_1(age)

## List Comprehension  using function ##

mylst1= [1, 2, 3, 4, 5]
mylst2= [6, 7, 8, 9, 10]

def combine_lists(lst1, lst2):
   combined= lst1 + lst2
   return combined

result= combine_lists(mylst1, mylst2)
print("Combined List:", result) 


## list comprehension single line ##
square= [y**2 for y in range(1, 11)]

print("Squares from 1 to 10:", square)

### Factorial of a number-

def factorial(n):
    if n < 0:
        return "Factorial is not defined for negative numbers."
    elif n == 0 or n == 1:
        return 1
    else:
        result = 1
        for i in range(2, n + 1):
            result *= i
        return result

num = 5
print(f"The factorial of {num} is {factorial(num)}") 

### map function ###

lst= [20, 30, 50, 70, 90]

def num(x):
    return x**2

result= map(num, lst)
print(list(result))

### filter function ###

def even(x):
    return x%2==0  
result= filter(even, lst)
print(list(result))

### reduce function ###


from functools import reduce
def add(x, y):
    return x+y
result= reduce(add, lst)
print(result)
