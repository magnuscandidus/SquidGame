# SquidGame
# cook your dish here
t=int(input())
while t:
    n=int(input())
    a=list(map(int,input().split()))
    b=min(a)
    c=sum(a)
    d=c-b
    print(d)
    t-=1
