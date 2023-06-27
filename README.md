# Broken-Phone
t=int(input())
while t:
    x,y=map(int,input().split())
    if(x>y):
        print("NEW PHONE")
    elif(x<y):
        print("REPAIR")
    else:
        print("ANY")
    t-=1
