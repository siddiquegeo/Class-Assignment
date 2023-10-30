# NN&AI 

# Assignment-02

# Arithmetic Operators

A

H


```python
H
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[2], line 1
    ----> 1 H
    

    NameError: name 'H' is not defined



```python
B

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[3], line 1
    ----> 1 B
    

    NameError: name 'B' is not defined


B

A

DD


Z


# M


4+6 = 

4+6=

# 4+6

4+6+5 

# 2+4+9 =




```python
3+5+4+3
```




    15




```python
23+48+345
46+2662+4747
```




    7455



# 46+37
# 38+477


```python
4628+2827
```




    7455




```python
7464-123
```




    7341




```python
4628*363
636-322
```




    314




```python
627-22
```




    605




```python
3526*362
```




    1276412




```python
66/2
```




    33.0




```python
66//2
```




    33




```python
67/2
```




    33.5




```python
67//2
```




    33




```python
239729/56
```




    4280.875




```python
239729//56
```




    4280




```python
2863//34
```




    84




```python
6*3
```




    18




```python
6**3
```




    216




```python
45*5
```




    225




```python
45**5
```




    184528125




```python
26%4
```




    2




```python
26%%4
```


      Cell In[27], line 1
        26%%4
           ^
    SyntaxError: invalid syntax
    



```python
26%5
```




    1




```python
35%5
```




    0



# Print function


```python
"34,45,43,55"

```




    '34,45,43,55'




```python
# Description
name = "siddique"
age = 34
profession = "geologist"

```


```python
#
print (name)
print (age)
print (profession)
```

    siddique
    34
    geologist
    


```python
#
name = "ahmad"
age = "24"
profession = 'agrarian'
```


```python
#
print (name)
print (age)
print (profession)
```

    ahmad
    24
    agrarian
    


```python
age = 30
name = "bilal"
print(name)
print(age)
```

    bilal
    30
    

# string format in print() function


```python
str = "hello Mr. %s, you are %s years old." %(name, age)
```


```python
# 
print ("hello Mr. %s, you are %s years old, %s profession." %(name, age, profession))
```

    hello Mr. ahmad, you are 24 years old, agrarian profession.
    


```python
#
name = 'bilal'
age = '30'
professoon = 'dvm'
country = 'uk'
```


```python
#
print (name)
print (age)
print (profession)
print (country)
```

    bilal
    30
    agrarian
    uk
    


```python
str = "hello Mr. %s, you are %s years old, %s profession, %s country." %(name, age, profession, country)
```


```python
# 
print ("hello Mr. %s, you are %s years old, %s profession, %s country."  %(name, age, profession, country))
```

    hello Mr. bilal, you are 30 years old, agrarian profession, uk country.
    


```python
str = "name %s, age %s, profession %s, %s country". %(name, age, profession,country)
```


```python
#
print ("hello Mr. %s, you are %s years old, %s profession, %s country."  %(name, age, profession, country))
```

    hello Mr. bilal, you are 30 years old, agrarian profession, uk country.
    


```python
?
?print

```


```python
help(print)
```

    Help on built-in function print in module builtins:
    
    print(*args, sep=' ', end='\n', file=None, flush=False)
        Prints the values to a stream, or to sys.stdout by default.
        
        sep
          string inserted between values, default a space.
        end
          string appended after the last value, default a newline.
        file
          a file-like object (stream); defaults to the current sys.stdout.
        flush
          whether to forcibly flush the stream.
    
    

# Variables and its different functions



```python
name_of_instructor = "Nadeem Majeed"
name_of_instructor 
type (name_of_instructor)
```




    str




```python
no_of_lectures = [34,44,23]
no_of_lectures
type (no_of_lectures)
```




    list



var1 = 33



```python
var1 =33
type (var1)

```




    int




```python
a= range (10)
#print(a)
#print(list(a))
```


```python
type(a)
```




    range



# assigning multiple values to multiple variables


```python
# 
a,b,c,d = 3,4,5.6,"saya" 

print ('a =',a,' b =',b,' c =',c, ' d =',d)

```

    a = 3  b = 4  c = 5.6  d = saya
    

# To Check the Type of a Variable


```python
name = "Nadeem Majeed"
print("name is of ", type(name))
x = 234
print("x is of ", type(x))
y = 5.321
print("y is of ", type(y))
```

    name is of  <class 'str'>
    x is of  <class 'int'>
    y is of  <class 'float'>
    

# check id of a variable


```python
x = 34
y = 22
z = 21
id (x), id(y), id(z)
```




    (140707996866376, 140707996865992, 140707996865960)




```python
a = 44
b = 22
id (a), id(b)
```




    (140707996866696, 140707996865992)




```python
a = 2
b = 2
id(a), id (b)
```




    (140707996865352, 140707996865352)




```python
var1 = "data science 1" 
id (var1)
```




    1330186746992




```python
print(dir())
```

    ['In', 'Out', '_', '_10', '_11', '_12', '_13', '_14', '_15', '_16', '_17', '_18', '_19', '_20', '_21', '_22', '_23', '_24', '_25', '_26', '_28', '_29', '_30', '_67', '_68', '_7', '_71', '_73', '_8', '_90', '_91', '_92', '_93', '__', '___', '__builtin__', '__builtins__', '__doc__', '__loader__', '__name__', '__package__', '__spec__', '_dh', '_i', '_i1', '_i10', '_i11', '_i12', '_i13', '_i14', '_i15', '_i16', '_i17', '_i18', '_i19', '_i2', '_i20', '_i21', '_i22', '_i23', '_i24', '_i25', '_i26', '_i27', '_i28', '_i29', '_i3', '_i30', '_i31', '_i32', '_i33', '_i34', '_i35', '_i36', '_i37', '_i38', '_i39', '_i4', '_i40', '_i41', '_i42', '_i43', '_i44', '_i45', '_i46', '_i47', '_i48', '_i49', '_i5', '_i50', '_i51', '_i52', '_i53', '_i54', '_i55', '_i56', '_i57', '_i58', '_i59', '_i6', '_i60', '_i61', '_i62', '_i63', '_i64', '_i65', '_i66', '_i67', '_i68', '_i69', '_i7', '_i70', '_i71', '_i72', '_i73', '_i74', '_i75', '_i76', '_i77', '_i78', '_i79', '_i8', '_i80', '_i81', '_i82', '_i83', '_i84', '_i85', '_i86', '_i87', '_i88', '_i89', '_i9', '_i90', '_i91', '_i92', '_i93', '_i94', '_ih', '_ii', '_iii', '_oh', 'a', 'age', 'arr', 'b', 'c', 'country', 'd', 'exit', 'get_ipython', 'i', 'j', 'n', 'name', 'name_of_instructor', 'no_of_lectures', 'open', 'profession', 'professoon', 'quit', 'str', 'var1', 'x', 'y', 'z']
    


```python
var2 = "venom"
id (var2)
```




    1330187725872




```python
print(dir())
```

    ['In', 'Out', '_', '_10', '_11', '_12', '_13', '_14', '_15', '_16', '_17', '_18', '_19', '_20', '_21', '_22', '_23', '_24', '_25', '_26', '_28', '_29', '_30', '_67', '_68', '_7', '_71', '_73', '_8', '_90', '_91', '_92', '_93', '_95', '__', '___', '__builtin__', '__builtins__', '__doc__', '__loader__', '__name__', '__package__', '__spec__', '_dh', '_i', '_i1', '_i10', '_i11', '_i12', '_i13', '_i14', '_i15', '_i16', '_i17', '_i18', '_i19', '_i2', '_i20', '_i21', '_i22', '_i23', '_i24', '_i25', '_i26', '_i27', '_i28', '_i29', '_i3', '_i30', '_i31', '_i32', '_i33', '_i34', '_i35', '_i36', '_i37', '_i38', '_i39', '_i4', '_i40', '_i41', '_i42', '_i43', '_i44', '_i45', '_i46', '_i47', '_i48', '_i49', '_i5', '_i50', '_i51', '_i52', '_i53', '_i54', '_i55', '_i56', '_i57', '_i58', '_i59', '_i6', '_i60', '_i61', '_i62', '_i63', '_i64', '_i65', '_i66', '_i67', '_i68', '_i69', '_i7', '_i70', '_i71', '_i72', '_i73', '_i74', '_i75', '_i76', '_i77', '_i78', '_i79', '_i8', '_i80', '_i81', '_i82', '_i83', '_i84', '_i85', '_i86', '_i87', '_i88', '_i89', '_i9', '_i90', '_i91', '_i92', '_i93', '_i94', '_i95', '_i96', '_ih', '_ii', '_iii', '_oh', 'a', 'age', 'arr', 'b', 'c', 'country', 'd', 'exit', 'get_ipython', 'i', 'j', 'n', 'name', 'name_of_instructor', 'no_of_lectures', 'open', 'profession', 'professoon', 'quit', 'str', 'var1', 'var2', 'x', 'y', 'z']
    


```python
del var1 
print(dir())
```

    ['In', 'Out', '_', '_10', '_11', '_12', '_13', '_14', '_15', '_16', '_17', '_18', '_19', '_20', '_21', '_22', '_23', '_24', '_25', '_26', '_28', '_29', '_30', '_67', '_68', '_7', '_71', '_73', '_8', '_90', '_91', '_92', '_93', '_95', '__', '___', '__builtin__', '__builtins__', '__doc__', '__loader__', '__name__', '__package__', '__spec__', '_dh', '_i', '_i1', '_i10', '_i11', '_i12', '_i13', '_i14', '_i15', '_i16', '_i17', '_i18', '_i19', '_i2', '_i20', '_i21', '_i22', '_i23', '_i24', '_i25', '_i26', '_i27', '_i28', '_i29', '_i3', '_i30', '_i31', '_i32', '_i33', '_i34', '_i35', '_i36', '_i37', '_i38', '_i39', '_i4', '_i40', '_i41', '_i42', '_i43', '_i44', '_i45', '_i46', '_i47', '_i48', '_i49', '_i5', '_i50', '_i51', '_i52', '_i53', '_i54', '_i55', '_i56', '_i57', '_i58', '_i59', '_i6', '_i60', '_i61', '_i62', '_i63', '_i64', '_i65', '_i66', '_i67', '_i68', '_i69', '_i7', '_i70', '_i71', '_i72', '_i73', '_i74', '_i75', '_i76', '_i77', '_i78', '_i79', '_i8', '_i80', '_i81', '_i82', '_i83', '_i84', '_i85', '_i86', '_i87', '_i88', '_i89', '_i9', '_i90', '_i91', '_i92', '_i93', '_i94', '_i95', '_i96', '_i97', '_ih', '_ii', '_iii', '_oh', 'a', 'age', 'arr', 'b', 'c', 'country', 'd', 'exit', 'get_ipython', 'i', 'j', 'n', 'name', 'name_of_instructor', 'no_of_lectures', 'open', 'profession', 'professoon', 'quit', 'str', 'var2', 'x', 'y', 'z']
    

# Numeric Data Type


```python
a = 40
b = 30.6
c = complex(2, 8)  
d = 6 + 9j
e = False
print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
```

    <class 'int'>
    <class 'float'>
    <class 'complex'>
    <class 'complex'>
    <class 'bool'>
    


```python
# 
x = 25 < 50
print(x)
print(type(x))
```

    True
    <class 'bool'>
    


```python
# 
x = 45 + True 
y = False + 24

print("x:", x)
print("y:", y)
```

    x: 46
    y: 24
    


```python
bool (0)
```




    False




```python
bool (False)
```




    False




```python
var1 = None
```


```python
type (var1)
```




    NoneType



# conversion

# implicit conversion


```python
a = 4 + 6
b = 1 + 5.0
type(a), type(b)
```




    (int, float)




```python
a = 4/2
b = 4/2.0
type(a), type(b)
```




    (float, float)



# explicit conversion


```python
x = '21'
type(x), x
```




    (str, '21')




```python
y = int(x)
type(y), y
```




    (int, 21)




```python
z = bool(-5)
type(z), z
```




    (bool, True)




```python
a = 54
type(a), a
```




    (int, 54)




```python
b = float(a)
type(b), b
```




    (float, 54.0)




```python
#
id(a), id(b)
```




    (140707996867016, 1330186431696)




```python
num = 341
type(num), num
```




    (int, 341)




```python
a = 2.6
b = 3.2
x = complex(a,b)
type(x), x
```




    (complex, (2.6+3.2j))




```python

```
