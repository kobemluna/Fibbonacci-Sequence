# Kobe Luna
# StudentID= 21590963
# Homework 1, problem 2

def fibon(x):
    if x<=1:
        return x
    else:
        return fibon(x-1)+fibon(x-2)

seq=int(input("How many interations?"))

if seq<=0:
    print("Enter a integer more than 0")
else:
    print("Fibonacci sequence: ")
    for y in range(seq):
        print(fibon(y))

