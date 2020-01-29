# Beginner-project-solutions
Solution to find out whether a number is Armstrong or not

n=int(input ("enter a number:")) 
l=len(str(n)) 
s=0
num=n
for I in range(n) :
    r=num%10
    s=s+r
    num=num%10
if(s==n):
  print("it is a armstrong number") 
else:
   print ("it is not a armstrong number") 
