## python 数据类型专项类型

### 列表（list）

#### 基本用法

1、列表常用的函数练习

请输出以下各题打印出的值

```python
A=[1,2,3,4,5]
print(A[4])


A=[1,2,3,4,5]
A.append(6)
print(A)

numbers = [1, 2, 3, 4]
numbers.append([5,6,7,8])
print(len(numbers))

A=[1,2,3,4,5]
A.insert(1,4)
print(A)

A=[1,2,3,4,5]
A.pop()
print(A)

A=[1,2,3,4,5]
A.pop(3)
print(A)

A=[1,2,3,4,5]
del A[2]
print(A)

A=[1,2,3,4,5]
A.remove(3)
print(A)

A=[1,2,3,4,5]
B=[6,7,8,9,10]
A.extend(B)
print(A)

A=[1,1,2,3,4,5]
print(A.count(1))

A=[1,1,2,3,4,5]
print(A.index(2))
```



2、操作列表的方法

请输出以下各题打印出的值

```
A=[1,2,3,4,5]
for index,value in enumerate(A):
    print(index)
    print(value)
       
A=[1,2,3,4,5]
print(len(A))

A=[1,2,3,4,5]
print(max(A))

A=[1,2,3,4,5]
print(min(A))

A=list("12345")
print(A)
```



3、列表切片练习

请输出以下各题打印出的值

```python
A=[1,2,3,4,5]
print(A[::2])
print(A[-2:])
print(A[4::-2])
```

4、遍历列表的值

请编写代码实现下面题目

```python
#遍历列表A的值并打印，代码写在下面
A=[1,2,3,4,5]



#打印出列表下标是2的倍数的值，代码写在下面
A=[1,2,3,4,5]



#使用for循环实现列表计算列表A的和
A=[1,2,3,4,5]



```

5、列表排序和反转

请输出以下各题打印出的值

```
A=[1,2,3,4,5]
A.reverse()
print(A)


A=[1,2,3,4,5]
A.sort()
print(A)

A=[1,2,4,3,5]
print(sorted(A))

#用sorted将字典列表中的字典元素按照age键进行排序
A=[{"name":"xiaoming","age":11},{"name":"xiaohong","age":9},{"name":"xiaomei","age":13}]

```



6、列表生成式

请编写代码实现下面题目

```
#使用列表解析式找出同时出现在b1和b2列表中元素
b1=[1,2,3]
b2=[2,3,4]

#使用列表解析式计算列表A的和
A=[1,2,3,4,5]

```

#### 综合题

```
#找出names列表中名字中包含两个a的名字，输出为一个新的列表
names = ["Andrea", "Aaslay", "Steven", "Joa"]


#一个非空int列表，其中有一种元素只出现一次，其他元素均出现两次，请输出那个只出现一次的元素
如[1,2,2],输出1，[2,3,3,4,2]输出4（可不考虑算法复杂度）


```











