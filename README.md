# calculator
a = int(input("Enter your first No.: "))
b = int(input("Enter your second No.: "))
sum = a + b
subtract = a - b
multiply = a * b
division = a / b
Z = input('What operation do you want to do: ')

if(Z == "+"):
    print(sum)
elif(Z == "-"):
    print(subtract)
elif(Z == "*"):
    print(multiply)
else:
    print(division)
