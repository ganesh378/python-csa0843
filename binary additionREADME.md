a=int(input("enter a binary number"))

b= int(input("enter another binary number"))

a=str(a)

b=str(b)

c=bin(int(a,2)+int(b,2))

print(c[2:])
