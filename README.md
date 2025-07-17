#fibnaci series
def fib(n):
    if n<=1:
        return n
    else:
        return fib(n-1)+fib(n-2)
num=int(input())
for i in range(num):
    print(fib(i),end=' ')

    def dsum(n):
    if n==0:
        return 0
    return n%10+temp(n//10)
def temp(n):
    return dsum(n)
num=int(input())
print("sum of digits:",dsum(num))

def one(n):
    if n==0:
        return True
    else:
        return two(n-1)
def two(n):
    if n==0:
        return False
    else:
        return one(n-1)
num=int(input())
if one(num):
    print(num,"is even number")
else:
    print(num,"is odd number")

def A(n):
    if n<=0:
        return 
    print('sravya',n)
    B(n-1)
def B(n):
    if n<=0:
        return
    print('laddika',n)
    A(n-1)
num=int(input("enter the number:"))
A(num)
