### Continuing to learn python

This new section will go over my Python knowledge from 2021 onward:

##### Break keyword (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:22 am**

```python
print("Break")
break
```

_(i) this is newer knowledge from 2021.._

**This section was last updated on 2021, Tuesday, October 5th at 1:03 pm**

#### Prior knowledge of the Python programming language

This section goes over my prior knowledge of Python (before the year 2020)

##### Hello world (python)

```python
print ("Hello world")
```

Here is a version more suitable for displaying the message for more than 0.01 seconds:

```python
print ("Hello world")
noMore = input("Press [ENTER] key to continue")
```

**This section was last updated on 2021, Tuesday, October 5th at 12:20 am**

##### Functions (python)

```python
def functionOne():
	print ("Function one")
	x = int(2)
	y = int(16)
	print (x ** y)
# Main thread
return functionOne()
```

This should output:

```text
Function one
65536
```

**This section was last updated on 2021, Tuesday, October 5th at 12:21 am**

##### Lists (python)

```python
list123 = ["1", "2", "3"]
print (str(list123))
noMore = input("Press [ENTER] key to quit")
```

_(i) This example may have problems._

**This section was last updated on 2021, Tuesday, October 5th at 1:09 pm**

##### Arrays (python)

```python
array2D = ["entry1", "entry2", "entry3"]
print (str(array2D))
noMore = input("Press [ENTER] key to quit")
```

_(i) This example may have problems._

**This section was last updated on 2021, Tuesday, October 5th at 1:08 pm**

##### Input (python)

```python
strInput = str(input("String input: "))
print ("You typed: " + str(strInput))
intInput = int(input("Integer input (enter a number): "))
print ("You typed: " + str(intInput))
miscInput = input("Miscellaneous input (enter anything): "))
print ("You typed: " + str(miscInput))
noMore = input("Press [ENTER] key to quit")
# Can booleans be an input value?
```

**This section was last updated on 2021, Tuesday, October 5th at 1:07 pm**

##### Variables (python)

```python
x = int(2)
p = float(3.14)
print (x + " " + p)
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:02 pm**

##### Booleans (python)

```python
trueFalse = bool(true)
falseTrue = bool("false")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:02 pm**

##### Break keyword (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:22 am**

```python
print("Break")
break
```

_(i) this is newer knowledge from 2021. It should be moved out of this section._

**This section was last updated on 2021, Tuesday, October 5th at 1:03 pm**

##### Upper keyword (python)

```python
inputLowercase = str(input("Enter something with at least 1 lowercase letter: "))
inputLowercase == inputLowercase.upper()
print ("Uppercase: " + str(inputLowercase))
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:05 pm**

##### Elif (python)

```python
inputELF = str(input("Do you like Python (y/N)"))
inputELF == inputELF.upper()
if (inputELF == "Y" or "YES"):
	print ("HE IS THE MESSIAH!")
elif (inputELF == "N" or "NO"):
	print ("sssssssssssssssss")
else:
	print ("Invalid input. Please enter Y, YES, N, or NO")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:12 pm**

##### If/else (python)

```python
input1 = str(input("Do you like Python (y/N)"))
input1 == input1.upper()
if (input1 == "Y" or "YES"):
	print ("HE IS THE MESSIAH!")
else:
	print ("ssssssssssssssssss")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:13 am**

##### Strings (python)

```python
stringy = str(input("Enter some text: "))
print (str(stringy))
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:14 pm**

##### Concatenation (python)

```python
con1 = str(input("Enter a name: "))
cat2 = int(input("Enter an age: "))
ena3 = str(input("Enter a fruit: "))
tion = float(input("Enter the first 3 numbers of Pi with a decimal: "))
print ("Your name is " + str(con1)) + " and you just turned " + str(cat2) + " years old. You wanted to stop aging, you so ate a magical " + str(ena3) + " and now Pi is ready: " + str(tion))
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:17 pm**

##### Loops (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:23 am**

###### While loop (python)

```python
xwhile = int(0)
while (x == 0):
	print ("Recursion")
	stop1 = int(input("Enter the answer to the universe to stop the loop: "))
	if (stop1 == 42):
		xwhile == 1
	else:
		print ("Wrong answer. The recursion continues")
print ("You now hold the secret to the universe")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:20 pm**

###### For loop (python)

```python
ra = str("ra")
for x in range(1, 2):
	print (str(ra))
print ("Rasputin")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:21 pm**

###### Random (python)

```python
import random
randomNum = random(randint(0, 9))
print ("The randomizer chose: " + str(randomNum))
noMore = input("Press [ENTER] key to quit")
```

_(i) This example may have problems._

**This section was last updated on 2021, Tuesday, October 5th at 1:23 pm**

##### File IO (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:24 am**

###### Writing to a file (python)

```python
f = open("test.txt", "a")
f.write("This is a test file")
f.close()
```

**This section was last updated on 2021, Tuesday, October 5th at 1:30 pm**

###### Reading a file (python)

```python
# open and read the file
f = open("test.txt", "r")
print(f.read()) 
```

**This section was last updated on 2021, Tuesday, October 5th at 1:32 pm**

##### Classes (python)

```python
class computerScience2018():
	print ("In 2018, I began learning Python in computer science class")
	noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:24 pm**

##### Objects (python)

```python
def object1():
	print ("Block")
	bblock = int(4)
	print (str(bblock) + " sides")
return object1()
```

**This section was last updated on 2021, Tuesday, October 5th at 1:34 pm**

###### Object Oriented Programming (python)

```python
def object2():
	print ("Triangle")
	btri = int(3)
	print (str(btri) + " sides")
object2()
```

**This section was last updated on 2021, Tuesday, October 5th at 1:35 pm**

##### Basic calculator (python)

```python
a = int(input("Addition calculator:\nEnter the first number: "))
b = int(input("Num2: "))
c = int(input("Num3: "))
sum = int(a + b + c)
print ("Sum (answer): " + str(sum))
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:37 pm**

##### Basic options menu (python)

```python
sfxIO = bool(true)
musicIO = bool(true)
print ("Audio settings:\n")
sfxC = str(input("Sound effects (y/N))
sfxC == sfxC.upper()
if (sfxC == "Y" or "YES"):
	sfxIO == bool(true)
else:
	sfxIO == bool(false)
musicC = str(input("Music (y/N))
musicC == musicC.upper()
if (musicC == "Y" or "YES"):
	musicIO == bool(true)
else:
	musicIO == bool(false)
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:40 pm**

##### Escape characters (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:26 am**

###### Newline (python)

```python
print ("The names text\n\n\n\n\n\nBottom text")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:25 pm**

###### Tab (python)

```python
print ("Tabby\tLikes\tTo\tTab")
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:25 pm**

##### Exponentiation (python)

```python
# 2 to the power of 16
x = int(2)
y = int(16)
z = int(x ** y)
print ("2^16 == " + str(z))
noMore = input("Press [ENTER] key to quit")
```

**This section was last updated on 2021, Tuesday, October 5th at 1:26 pm**

##### Error handling (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:27 am**

###### Try (python)

This example will throw an error, as x is not defined.

```python
try:
	print(x)
except:
	print("An exception occurred") 
```

This example will NOT throw an error, as x IS defined.

```python
x = int(1)
try:
	print(x)
except:
	print("An exception occurred") 
```

**This section was last updated on 2021, Tuesday, October 5th at 1:48 pm**

###### Except (python)

This example will throw an error, as x is not defined.

```python
try:
	print(x)
except:
	print("An exception occurred") 
```

This example will NOT throw an error, as x IS defined.

```python
x = int(1)
try:
	print(x)
except:
	print("An exception occurred") 
```

**This section was last updated on 2021, Tuesday, October 5th at 1:48 pm**

##### Comments (python)

**This section was last updated on 2021, Tuesday, October 5th at 12:27 am**

###### Single line comments (python)

```python
# This is a single line comment
```

**This section was last updated on 2021, Tuesday, October 5th at 1:27 pm**

###### Block comments (python)

```python
''' Block comment A
This is a block comment
'''
""" Block comment B
Block comments can also be written like this.
"""
```

**This section was last updated on 2021, Tuesday, October 5th at 1:27 pm**

##### Other (python)

about:unknown$notFound

**This section was last updated on 2021, Tuesday, October 5th at 12:24 am**

##### Other (python)

More examples coming soon.
