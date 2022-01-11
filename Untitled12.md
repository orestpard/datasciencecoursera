```python
s = "Python"
print(s[0])

```

    P
    


```python
print(len(s))
```

    6
    


```python
mylist = ["paok", "garcia", 4]
print(mylist)
```

    ['paok', 'garcia', 4]
    


```python
print(mylist[-1])
```

    4
    


```python
print(mylist[2])
```

    4
    


```python
seq = [45,96,87,52,31,21,45,89,72,35,69,88,55,33,66]
seq[1:5]
```




    [96, 87, 52, 31]




```python
mylist1 = [3,67,"cat",[57,56,"dog"], [],3.14, False]
print(mylist1[4:])
```

    [[], 3.14, False]
    


```python
sub_list = mylist1[2:4]
```


```python
print(sub_list)
```

    ['cat', [57, 56, 'dog']]
    


```python
mylist1.sort()

```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-13-3170c3202c2c> in <module>
    ----> 1 mylist1.sort()
    

    TypeError: '<' not supported between instances of 'str' and 'int'



```python
mylist2 = [4,78,98,6,3,45,85,66]
```


```python
mylist2.sort()
```


```python
b = "Up the Irons"
print(b.count("I"))
```

    1
    


```python
list(reversed(range(45)))
```




    [44,
     43,
     42,
     41,
     40,
     39,
     38,
     37,
     36,
     35,
     34,
     33,
     32,
     31,
     30,
     29,
     28,
     27,
     26,
     25,
     24,
     23,
     22,
     21,
     20,
     19,
     18,
     17,
     16,
     15,
     14,
     13,
     12,
     11,
     10,
     9,
     8,
     7,
     6,
     5,
     4,
     3,
     2,
     1,
     0]




```python
song = "Afraid to shoot straingers"
im = song.split()
```


```python
print(im)
```

    ['Afraid', 'to', 'shoot', 'straingers']
    


```python
song1 = ["fear","of","the","Dark"]
glue = ' '
s = glue.join(song1)
print(s)

```

    fear of the Dark
    


```python
let = "z"
let_two = "p"
c = let_two + let
m = c*5
print(m)
```

    pzpzpzpzpz
    


```python
ls = ['run','world','travel','lights','moon','baseball','sea']
new = ls[2:4]
print(new)
```

    ['travel', 'lights']
    


```python
l = ['w', '7', 0, 9]
m = l[1]
```


```python
print(type(m))
```

    <class 'str'>
    


```python
b = "My, what a lovely day"
x = b.split(',')
```


```python
print(type(x)
```


      File "<ipython-input-35-9aade63a955a>", line 1
        print(type(x)
                     ^
    SyntaxError: unexpected EOF while parsing
    



```python
b = "My, what a lovely day"
x = b.split(',')
```


```python
print(type(x))
```

    <class 'list'>
    


```python
b = "My, what a lovely day"
x = b.split(',')
z = "".join(x)
y = z.split()
a = "".join(y)
```


```python
print(type(a))
```

    <class 'str'>
    


```python
lst = ["hi", "goodbye", "python", "106", "506", 91, ['all', 'Paul', 'Jackie', "UMSI", 1, "Stephen", 4.5], 109, "chair", "pizza", "wolverine", 2017, 3.92, 1817, "account", "readings", "papers", 12, "facebook", "twitter", 193.2, "snapchat", "leaders and the best", "social", "1986", 9, 29, "holiday", ["women", "olympics", "gold", "rio", 21, "2016", "men"], "26trombones"]
```


```python
num_list = list

```


```python
num_list = list.count(number)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-45-45486eb36dec> in <module>
    ----> 1 num_list = list.count(number)
    

    NameError: name 'number' is not defined



```python
for name in ["Joe","Steve","Bruce"]:
    print("Up the irons!!")

```

    Up the irons!!
    Up the irons!!
    Up the irons!!
    


```python
for name in ["Joe","Steve","Bruce"]:
    print(name,"Up the irons!!")
```

    Joe Up the irons!!
    Steve Up the irons!!
    Bruce Up the irons!!
    


```python
s = "python rocks"
for ch in s:
    print("HELLO")
```

    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    


```python
s = "python rocks"
for ch in s[3:8]:
    print("HELLO")
```

    HELLO
    HELLO
    HELLO
    HELLO
    HELLO
    


```python
nums = [1,2,3,4,5,6,7,8,9,10]
accum = 0
for w in nums:
    accum = accum + w
print(accum)
```

    55
    


```python
nums = [1,2,3,4,5,6,7,8,9,10]
accum = 0
for w in nums:
    accum = accum + w
    print(accum)
```

    1
    3
    6
    10
    15
    21
    28
    36
    45
    55
    


```python
nums = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]

print("range(5): ")
for i in range(5):
    print(i)
```

    range(5): 
    0
    1
    2
    3
    4
    


```python
nums = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]

print("range(0,5): ")
for i in range(0,5):
    print(i)
```

    range(0,5): 
    0
    1
    2
    3
    4
    


```python
nums = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]

print("range(7,15): ")
for i in range(7,15):
    print(i)
```

    range(7,15): 
    7
    8
    9
    10
    11
    12
    13
    14
    


```python
nums = [1,2,3,4,5,6,7,8,9,10]
nums = range(1,11)
accum = 0
for w in nums:
    accum = accum + w
print(accum)
```

    55
    


```python
for y in x:
    print(y)
```

    My
     what a lovely day
    


```python
w = range(10)
tot = 0
for num in w :
    print(num)
    tot +=num
    print(tot)
print(tot)
```

    0
    0
    1
    1
    2
    3
    3
    6
    4
    10
    5
    15
    6
    21
    7
    28
    8
    36
    9
    45
    45
    


```python
print(int(53.785))
```

    53
    


```python
for x in array:
    if x < pivot:
        less.append(x)
    else:
        greater.append(x)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-60-ffad9157dda0> in <module>
    ----> 1 for x in array:
          2     if x < pivot:
          3         less.append(x)
          4     else:
          5         greater.append(x)
    

    NameError: name 'array' is not defined



```python
x
if x < 0:
    print("It's negative")
elif x == 0:
    PRINT("Equal to zero")
else:
    print("Positive")
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-62-250585d55f78> in <module>
          1 x
    ----> 2 if x < 0:
          3     print("It's negative")
          4 elif x == 0:
          5     PRINT("Equal to zero")
    

    TypeError: '<' not supported between instances of 'list' and 'int'



```python
tup = tuple('string')
tup
```




    ('s', 't', 'r', 'i', 'n', 'g')




```python
tup = 4,8,78
tup
```




    (4, 8, 78)




```python
seq = [(1,2,3), (4,5,6), (7,8,9)]
for a,b,c in seq:
    print('a={0}, b={1}, c={2}'.format(a,b,c))
```

    a=1, b=2, c=3
    a=4, b=5, c=6
    a=7, b=8, c=9
    


```python
a = (1,2,5,8,79,5,4,6,3,4,4,8,7)
a.count(4)
```




    3




```python
gen=range(10)
gen
```




    range(0, 10)




```python
list(gen)
```




    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]




```python
list.append(45)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-72-fc53dc86eb29> in <module>
    ----> 1 list.append(45)
    

    TypeError: descriptor 'append' for 'list' objects doesn't apply to a 'int' object



```python
list1=[2,3,7,'numbers']
list1
```




    [2, 3, 7, 'numbers']




```python
list1.append(44)
```


```python
list1
```




    [2, 3, 7, 'numbers', 44]




```python
list1.insert(3,9)
list1
```




    [2, 3, 7, 9, 'numbers', 44]




```python
list1.pop(4)
list1
```




    [2, 3, 7, 9, 44]




```python
'numbers' in list1
```




    False




```python
print(5==5)
```

    True
    


```python
x = 5
print(x<0 and x>10)
```

    False
    


```python
n =25
print(n%2 == 1 or n%3 == 5)
```

    True
    


```python
print('p' in 'apple')
```

    True
    


```python
x=17
if x < 0:
    print("It's negative")
elif x == 0:
    PRINT("Equal to zero")
else:
    print("Positive")
```

    Positive
    


```python
phrase = "What a wonderful day to program"
tot = 0
for char in phrase:
    if char !=" ":
        tot = tot +1
print(tot)

```

    26
    


```python
nums = [9,3,8,11,5,29,2]
best_num = nums[1]
for n in nums:
    if n > best_num:
        best_num = n
print(best_num)
```

    29
    


```python
list =[5,2,1,4,9,10]
min_value = 4
for item in list:
    if item < min_value:
        min_value = item
print(min_value)
```

    1
    


```python
phrase = "many moons"
phrase_expanded = phrase + " and many stars"
phrase_larger = phrase_expanded + " litter"
phrase_complete = "M" + phrase_larger[1:] + " the night sky."
excited_phrase_complete = phrase_complete[:-1] + "!"
```


```python
alist = [4,2,8,6,5]
alist[2] = True
print(alist)
```

    [4, 2, True, 6, 5]
    


```python
w = ['Jamboree', 'get-together', 'party']
y = ['celebration']
y = w
```


```python
alist = [4,2,8,6,5]
blist = alist
blist[3] = 999
print(alist)
```

    [4, 2, 8, 999, 5]
    


```python
a = [81,82,83]
b = a[:]
print(a ==b)
print(a is b)
```

    True
    False
    


```python
print(b)
```

    [81, 82, 83]
    


```python
b[0] = 10
print(a)
```

    [81, 82, 83]
    


```python
print(b)
```

    [10, 82, 83]
    


```python
alist = [4,2,8,6,5]
blist = alist * 2
blist[3] = 999
print(alist)
```

    [4, 2, 8, 6, 5]
    


```python
b = ['q', 'u', 'i']
z = b
b[1] = 'i'
z.remove('i')
print(z)
```

    ['q', 'i']
    


```python
sent = "Holidays can be a fun time when you have good company!"
phrase = sent
phrase = phrase + " Holidays can also be fun on your own!"
```


```python
print(phrase)
```

    Holidays can be a fun time when you have good company! Holidays can also be fun on your own!
    


```python
lst = ['mercury', 'venus', 'earth', 'mars', 'jupiter', 'saturn', 'uranus', 'neptune', 'pluto']
lst.remove('pluto')
first_three = lst[:3]
```


```python
print(lst)
```

    ['mercury', 'venus', 'earth', 'mars', 'jupiter', 'saturn', 'uranus', 'neptune']
    


```python
x = ["dogs", "cats", "birds", "reptiles"]
y = x
x += ['fish', 'horses']
y = y + ['sheep']
print(y)
```

    ['dogs', 'cats', 'birds', 'reptiles', 'fish', 'horses', 'sheep']
    


```python
sent = "The mall has excellent sales right now."
wrds = sent.split()
wrds[1] = 'store'
new_sent = " ".join(wrds)
print(new_sent)
```

    The store has excellent sales right now.
    


```python
mylist = [5,78,96]

```


```python
mylist.append(5)
```


```python
mylist

```




    [5, 78, 96, 5]




```python
mylist.append(47)
```


```python
mylist
```




    [5, 78, 96, 5, 47]




```python
mylist.insert(55,66)
```


```python
print(mylist)
```

    [5, 78, 96, 5, 47, 66]
    


```python
print(mylist.count(5))
```

    2
    


```python
print(mylist.index(3))
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-124-cdb191c63e70> in <module>
    ----> 1 print(mylist.index(3))
    

    ValueError: 3 is not in list



```python
print(mylist.index(5))
```

    0
    


```python
mylist.sort(key=5)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-126-0a1c809f7ced> in <module>
    ----> 1 mylist.sort(key=5)
    

    TypeError: 'int' object is not callable



```python
mylist.sort()
```


```python
mylist
```




    [5, 5, 47, 66, 78, 96]




```python
mylist.pop(2)
```




    47




```python
mylist
```




    [5, 5, 66, 78, 96]




```python
mylist1 = mylist +["cast"]
```


```python
mylist1
```




    [5, 5, 66, 78, 96, 'cast']




```python
mylist1.extend([78,98,58])
```


```python
mylist1
```




    [5, 5, 66, 78, 96, 'cast', 78, 98, 58]




```python
template = '{0:.2f}' {1:s} are worth US${2:d}
template.format(4.5560, 'Argentine Pesos', 1)
```


      File "<ipython-input-136-79ba843022b9>", line 1
        template = '{0:.2f}' {1:s} are worth US${2:d}
                             ^
    SyntaxError: invalid syntax
    



```python
s = "Dance of Death"
els = s.count("D")
```


```python
s.count("D")
```




    2




```python
print(s.strip)
```

    <built-in method strip of str object at 0x000001A31AD70EF0>
    


```python
news = s.replace("o", "O")
```


```python
print(news)
```

    Dance Of Death
    


```python
print(s[1]*s.index("n"))
```

    aa
    


```python
name = "Steve Harris"
score = 4
print(  "Hello" " " + name + " " "Your score is" + " " str(score))
```


      File "<ipython-input-146-8ece2c66dd76>", line 3
        print(  "Hello" " " + name + " " "Your score is" + " " str(score))
                                                               ^
    SyntaxError: invalid syntax
    



```python
scores = [("Steve Harris", 4), ("Adrian Smith", 5)]
for person in scores:
    name = person[0]
    score = person[1]
    print("Hello {}. Your score is {}.".format(name,score))
```

    Hello Steve Harris. Your score is 4.
    Hello Adrian Smith. Your score is 5.
    


```python
price = float(input('Enter the price: $'))
discount = float(input('Enter discount percentage: '))
newprice = (1 - discount/100)*price
calculation = '${:.2f} discount by {}% is ${:.2f}.'.format(price, discount, newprice)
print(calculation)
```

    Enter the price: $89.99
    Enter discount percentage: 15.60
    $89.99 discount by 15.6% is $75.95.
    


```python
nums = [3, 5, 8]
accum = []
for w in nums:
    x=w**2
    accum.append(x)
print(accum)
```

    [9, 25, 64]
    


```python
nums = [3, 5, 8]
accum = []
for w in nums:
    x=w**2
    accum.append(x)
    print(accum)
```

    [9]
    [9, 25]
    [9, 25, 64]
    


```python
alist = [4, 2, 8, 6, 5]
blist = []
for item in alist:
    blist.append(item + 5)
print(blist)
```

    [9, 7, 13, 11, 10]
    


```python
lst= [3,0,9,4,1,7]
new_list=[]
for i in range(len(lst)):
   new_list.append(lst[i]+5)
print(new_list)

```

    [8, 5, 14, 9, 6, 12]
    


```python
verbs = ["kayak", "cry", "walk", "eat", "drink", "fly"]
new_ing = []
for item in verbs:
    new_ing.append(item + "ing")
print(new_ing)
```

    ['kayaking', 'crying', 'walking', 'eating', 'drinking', 'flying']
    


```python
numbs = [5, 10, 15, 20, 25]
new_numbs = []
for i in numbs:
    new_numbs.append(i + 5)
print(new_numbs)
```

    [10, 15, 20, 25, 30]
    


```python
lst_nums = [4, 29, 5.3, 10, 2, 1817, 1967, 9, 31.32]
larger_nums = []
for i in lst_nums:
    larger_nums.append(i*2)
print(larger_nums)

```

    [8, 58, 10.6, 20, 4, 3634, 3934, 18, 62.64]
    


```python
s = input("Enter some text")
ac = ""
for c in s:
    ac = ac + c + "-" + c + "-"

print(ac)

```

    Enter some textdog
    d-d-o-o-g-g-
    


```python
s = "ball"
r = ""
for item in s:
   r = item.upper() + r
print(r)

```

    LLAB
    


```python
output = ""

for i in range(0,35):
  output = output + 'a'
print(output)

```

    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
    


```python
x = [1, 2, 3]
y = x
x += [4, 5]
y = y + [6]
print(x)
print(y)
```

    [1, 2, 3, 4, 5]
    [1, 2, 3, 4, 5, 6]
    


```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Indigo", "Violet"]

for color in colors:
    print(color)
```

    Red
    Orange
    Yellow
    Green
    Blue
    Indigo
    Violet
    


```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Indigo", "Violet"]
initials = []

for color in colors:
    initials.append(color[0])

print(initials)
```

    ['R', 'O', 'Y', 'G', 'B', 'I', 'V']
    


```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Indigo", "Violet", "Purple", "Pink", "Brown", "Teal", "Turquois", "Peach", "Beige"]

for position in range(len(colors)):
    color = colors[position]
    print(color)
    if color[0] in ["P", "B", "T"]:
        del colors[position]

print(colors)
```

    Red
    Orange
    Yellow
    Green
    Blue
    Violet
    Purple
    Brown
    Turquois
    Beige
    


    ---------------------------------------------------------------------------

    IndexError                                Traceback (most recent call last)

    <ipython-input-167-3406d8ece12e> in <module>
          2 
          3 for position in range(len(colors)):
    ----> 4     color = colors[position]
          5     print(color)
          6     if color[0] in ["P", "B", "T"]:
    

    IndexError: list index out of range



```python
lst = ['mercury', 'venus', 'earth', 'mars', 'jupiter', 'saturn', 'uranus', 'neptune', 'pluto']
lst.remove('pluto')
first_three = lst[:3]
print(lst[:3])
```

    ['mercury', 'venus', 'earth']
    


```python
a = ["holiday", "celebrate!"]
quiet = a
quiet.append("company")
print(quiet)
```

    ['holiday', 'celebrate!', 'company']
    


```python
ael = "python!"
lst = []
for i in ael:
    lst.append(i)
    app = lst
print(lst)
```

    ['p', 'y', 't', 'h', 'o', 'n', '!']
    


```python
wrds = ["end", 'work', "play", "start", "walk", "look", "open", "rain", "learn", "clean"]
lst = []
for i in wrds:
    i = i + "ed"
    lst.append(i)
    past_wrds = lst
print(past_wrds)
```

    ['ended', 'worked', 'played', 'started', 'walked', 'looked', 'opened', 'rained', 'learned', 'cleaned']
    


```python
scores = "67 80 90 78 93 20 79 89 96 97 92 88 79 68 58 90 98 100 79 74 83 88 80 86 85 70 90 100"
lst = scores.split()
a_scores = 0
for i in lst:
    if int(i) >= 90:
        a_scores += 1
print(a_scores)
```

    10
    


```python
stopwords = ['to', 'a', 'for', 'by', 'an', 'am', 'the', 'so', 'it', 'and', "The"]
org = "The organization for health, safety, and education"
acro = " "
lst = org.split()
for i in lst:
    if i in stopwords:
        lst.remove(i)
        for j in lst:
            acro += j[0]
            acro = acro.upper()
print(acro)
```

     OFHSAEOHSAEOHSE
    


```python
stopwords = ['to', 'a', 'for', 'by', 'an', 'am', 'the', 'so', 'it', 'and', 'The']
sent = "The water earth and air are vital"
acro = " "
lst = sent.split()
for i in lst:
    if i in stopwords:
        lst.remove(i)
        for j in lst:
            acro = acro + j[0] + j[1]
            if j != lst[-1]:
                acro += "."
                acro = acro.upper()
print(acro)
```

     WA.EA.AN.AI.AR.VIWA.EA.AI.AR.vi
    


```python
p_phrase = "was it a car or a cat I saw"
r_phrase = p_phrase[::-1]
print(r_phrase)
```

    was I tac a ro rac a ti saw
    


```python
inventory = ["shoes, 12, 29.99", "shirts, 20, 9.99", "sweatpants, 25, 15.00", "scarves, 13, 7.75"]
for temp in inventory:
    temp = temp.split(',')
    str1 = "The store has {} {}, each for {} USD."
    str1 = str1.format(temp[1], temp[0], temp[2])
print(str1)
```

    The store has  13 scarves, each for  7.75 USD.
    


```python

```
