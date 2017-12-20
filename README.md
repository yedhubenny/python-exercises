
def add(x, y):
   return x + y
def subtract(x, y):
   return x - y
def multiply(x, y):
   return x * y
def divide(x, y):
   return x / y
print("choose the operation")
a=input("1.addition,2.subtraction,3.multiplication,4.division")

n1 = int(input("Enter first number: "))
n2 = int(input("Enter second number: "))

if a == '1':
   print(n1,"+",n2,"=", add(n1,n2))

elif a == '2':
   print(n1,"-",n2,"=", subtract(n1,n2))

elif a == '3':
   print(n1,"*",n2,"=", multiply(n1,n2))

elif a == '4':
   print(n1,"/",n2,"=", divide(n1,n2))
else:
   print("Invalid input")
