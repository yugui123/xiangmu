# xiangmu
#用for语句生成一个100项的平方数数列的list，即[1,4,9,16,...,10000]
list=[]
for t in range(101):
    if t == 0:
        continue
    list.append(t*t)
print(list)
#用for语句计算100项的平方数数列的和，即1+4+9+16+...+10000的结果
#方法一直接用sum函数
#方法二用for语句
sum=0
for x in list:
    sum+=x
print(sum)
