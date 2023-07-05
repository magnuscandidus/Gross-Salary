# Gross-Salary
# cook your dish here
t=int(input())
while t:
    x=int(input())
    if(x<1500):
        print(x+(0.1*x)+(0.9*x))
    else:
        print(x+500+(0.98*x))
    t-=1
