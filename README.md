#program to subtract two matrices
a=[]
m=int(input('enter number of rows: '))
n=int(input('enter number of columns: '))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    a.append(row)
print(a)
b=[]
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    b.append(row)
print(b)
result=[]
for i in range(m):
    row=[]
    for j in range(n):
        row.append(0)
    result.append(row)
for i in range(m):
    for j in range(n):
        result[i][j]=a[i][j]-b[i][j]
print('resultant matrix: ',result)
OUTPUT: enter number of rows: 3
enter number of columns: 3
1
2
3
4
5
6
7
8
9
[[1, 2, 3], [4, 5, 6], [7, 8, 9]]
4
5
6
7
8
9
1
23
4
[[4, 5, 6], [7, 8, 9], [1, 23, 4]]
resultant matrix:  [[-3, -3, -3], [-3, -3, -3], [6, -15, 5]]
