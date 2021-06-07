# assingment-1-
#question 1 
str ="hey i am from New Delhi"
print(len(str))
str.split()

#question 2
print(s.capitalize())
s1=s.replace("name","rame")
print(s1.title()) 
print(s.upper())

#question 3
a= int(input("length : "))
b= int(input("breadth : "))
area = a*b
print("Area of rectangle :",area)
perimeter = 2*(a+b)
print("Perimeter of rectangle :",perimeter)

#question 4
diameter= int(input("diameter :"))
radius = diameter/2
circumference= 22/7*2*radius
area= 22/7*radius*radius
print("Circumference of circle is :",circumference)
print("Area of circle is :",area)

#question 5
import math
a=float(input("a :"))
b=float(input("b :"))
c=float(input("c :"))
print("quadratic function : (a*x^2) + b*x +c")
r= b**2 - 4*a*c
if r>0:
  num_roots = 2
  x1 = (((-b) + sqrt(r))/2*a)
  x2 = (((-b) - sqrt(r))/2*a)
  print(" There are two roots :"(x1,x2))
elif r==0:
 num_roots =1
 x= -b/2*a
 print(" There is one root :",x)
else:
 num_roots=0
 print("no roots as discriminant <0 :")
 exit()
 
 #question 6
radius=int(input("radius :"))
volume=4/3*22/7*radius*radius*radius
print("The volume of sphere :",volume)

#question 7
a=int(input("enter number :"))
count=0
while(a>0):
  count=count+1
  a=a//10
print("Total number of digits in a number is  :",count)

#question 8
str=str(input("enter string :"))
print(str.upper())

#question 9
s=input("Enter String : ")
n=int(input("Enter Index : "))
c=input("Enter Character : ")
temp=list(s)
temp[n]=c
s=" ".join(temp)
print(s)


#question 10
s="hey there"[::-1]
print(s)


