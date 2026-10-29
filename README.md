fruits = ['apple','banana','mango','apple']
>>> print(fruits)
['apple', 'banana', 'mango', 'apple']
>>> fruits[0]
'apple'
>>> fruits[-1]
'apple'
>>> fruits[1:3]
['banana', 'mango']
>>> fruits[2] = 'orange'
>>> print(fruits)
['apple', 'banana', 'orange', 'apple']
>>> fruits[2:3]
['orange']
>>> fruits[-2]
'orange'
>>> nums = [5,6,9,2,4]
>>> nums.append(11)
>>> print(nums)
[5, 6, 9, 2, 4, 11]
>>> nums.insert(0,22)
>>> print(nums)
[22, 5, 6, 9, 2, 4, 11]
>>> nums.extend([33,44,55])
>>> print(nums)
[22, 5, 6, 9, 2, 4, 11, 33, 44, 55]
>>> num1 = [87,67,88]
>>> nums.extend(num1)
>>> print(nums)
[22, 5, 6, 9, 2, 4, 11, 33, 44, 55, 87, 67, 88]
>>> nums(1)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'list' object is not callable
>>> nums([1])
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'list' object is not callable
>>> nums[1]
5
>>> nums
[22, 5, 6, 9, 2, 4, 11, 33, 44, 55, 87, 67, 88]
>>> nums.pop()
88
>>> nums.reverse
<built-in method reverse of list object at 0x000001C4AF905100>
>>> nums.reverse()
>>> nums
[67, 87, 55, 44, 33, 11, 4, 2, 9, 6, 5, 22]
>>> nums.sort()
>>> nums
[2, 4, 5, 6, 9, 11, 22, 33, 44, 55, 67, 87]
>>> print(22 in nums)
True
