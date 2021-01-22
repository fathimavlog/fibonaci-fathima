# fibonaci-fathima
program for fibonacci using loops
a=0
b=1
n=int(input("enter the number of fibonacci to be generated"))
if n<=0:
print("not possible")
elif n==1:
print(a)
elif n>=2:
print("{},{}".format(a,b),end='')
for i in range(2,n):
c=a+b
print(",{}".format(c),end='')
a=b
b=c
output:enter the number of fibonacci to be generated:15
0,1,1,2,3,5,8,13,21,34,55,89,144,233,377
