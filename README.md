#Approach-1
n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
for j in d:
  print(d[j])

#Approach-2  
n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=d.values()
print(res)
