# 1234567
----^
# Program make a hard calculator

# This function adds three numbers
def add(x, y, z ):
    return x + y + z

# This function subtracts three numbers
def subtract(x, y, z):
    return x - y- -z

# This function multiplies three numbers
def multiply(x, y , z):
    return x * y * z

# This function divides three numbers
def divide(x, y , z):
    return x / y / z


print("Select operation.")
print("1.Add 3 numbers")
print("2.Subtract 3 numbers")
print("3.Multiply 3 numbers")
print("4.Divide 3 numbers")

while True:
    # take input from the user
    choice = input("Enter choice(1/2/3/4): ")
