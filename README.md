# 50 Simple Python Programs for Absolute Beginners

<hr>

1. How to print “Hello World” on Python?

```
print("Hello World")
```

2. How to print “Hello + Username” with the user’s name on Python?

```
usertext = input("What is your name? ")
print("Hello", usertext)
```

3. How to add 2 numbers entered on Python?

```
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

sum = float(num1) + float(num2)

print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))
```

4. How to find the Average of 2 Entered Numbers on Python?

```
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

average =(int(num1) + int(num2))

print('average:{0} '.format(average))
```

5. How to calculate the Entered Visa and Final Grade Average on Python?

```
visagrade = input('enter your visa grade : ')
finalgrade = input('enter your final grade : ')
average =(float(visagrade)*0.3)+(float(finalgrade)*0.7)
print("average :{0} ".format(average))
```

6. How to find the Average of 3 Written Grades entered on Python?

```
firstexam = input('your first exam : ')
secondexam = input('your second exam : ')
thirdexam = input('your third exam : ')
average =(float(firstexam)+float(secondexam)+float(thirdexam))/3
print("average :{0} ".format(average))
```

7. How to show the Class Pass Status (PASSED — FAILED) of the Student whose Written Average Has Been Entered on Python?

```
average = input('enter average : ')
if(int(average)>=50):
print("Passed")
else:
print("Failed")
```

8. How to find out if the entered number is odd or even on Python?

```
num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))
```

9. How to find out if the entered number is Positive, Negative, or 0 on Python?

```
num = float(input("Enter a number: "))
if num > 0:
   print("Positive number")
elif num == 0:
   print("Zero")
else:
   print("Negative number")
```

10. How to calculate body mass index on Python?

```
print("body mass index calculation program")
height = float(input("enter height (m):"))
weight = int(input("enter weight (kg):"))

index  = weight/(height*height)

if index <=18:
    print("\n underweight BMİ:{}".format(index))
elif index > 18 and index <=25 :
    print("\n overweight BMİ:{}".format(index))
elif index > 25 and index <=30:
    print("\n obese BMİ:{}".format(index))
elif index > 30:
    print("\n severely obese BMİ:{}".format(index))

```

11. How to show if the person whose age is entered can get a driver’s license on Python?

```
age = input('enter age : ')
if(int(age)<18):
print("Your Age Is Not Eligible To Get A Driver's License")
else:
print("Your Age Is Eligible To Get Your License")

```

12. How to List Numbers 1–100 on the Screen on Python?

```
for i in range(1,101):
print(i)
```

13. How to List Even Numbers 1–100 on Python?

```
for i in range(1,101):
if i%2==0:
print(i)
```

14. How to List Odd Numbers from 1–100 on Python?

```
for i in range(1,101):
if i%2!=0:
print(i)
```

15. How to find numbers between 1 and 100 that are divided by 3 and 5 on Python?

```
for i in range(1,101):
if i%3==0 or i%5==0:
print(i)
```

16. How to list Numbers from 1 to User-Entered Number on Python?

```
num = input('enter number : ')
for i in range(1,int(num)+1):
print(i)
```

17. How to find the Area and Perimeter of a Rectangle With Its Sides on Python?

```
short = input('Enter short side : ')
tall = input('Enter tall side : ')
area = int(short)*int(tall)
perimeter =2*(int(short)+int(tall))
print("area: {0}".format(alan))
print("perimeter: {0}".format(cevre))
```

18. How to print the letters of the entered text one under the other on Python?

```
word = 'mrhuseyin'
for char in word:
    print(char)
```

19. How to show the sum of numbers between two numbers the user has entered on Python?

```
sumofnumbers=0;
num1 = input('first number: ')
num2 = input('second number: ')
for i in range(int(sayi1)+1,int(sayi2)):
sumofnumbers+=i
print("Sum of numbers between {0} and {1} : {2}".format(num1,num2,sumofnumbers))

```

20. For example, let’s ask the user about their choice of cinema or theater. You have to pay 10 dollars to watch movies and 5 dollars for theater. We think that students get 50% discount. If the student is discounted; If he is not a student, let’s write a document that calculates the non-discounted amount and prints it.

```
selection = input("Press (1) for Cinema, (2) for Theater : ")
student = input("Are you student(Y/N) : ")
price = 0
#non-discounted fee calculation
if selection == '1':
price = 10 #cinema
elif selection == '2':
price = 5 #theatre
#student discount
if student =='Y' or student =='y':
price=price / 2  #%50
print(" The fee you have to pay :{}".format(price))

```

21. How to find out if the entered number is Prime or Not on Python?

```
num = int(input("Enter a number: "))

if num > 1:
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           print(i,"times",num//i,"is",num)
           break
   else:
       print(num,"is a prime number")

else:
   print(num,"is not a prime number")
```
22. How to separately find the sum of odd and even numbers up to the number that the user has entered on Python?
```
NumList = []
Even_Sum = 0
Odd_Sum = 0

Number = int(input("Please enter the Total Number of List Elements: "))
for i in range(1, Number + 1):
    value = int(input("Please enter the Value of %d Element : " %i))
    NumList.append(value)

for j in range(Number):
    if(NumList[j] % 2 == 0):
        Even_Sum = Even_Sum + NumList[j]
    else:
        Odd_Sum = Odd_Sum + NumList[j]

print("\nThe Sum of Even Numbers in this List =  ", Even_Sum)
print("The Sum of Odd Numbers in this List =  ", Odd_Sum)
```
23. How to calculate the increased salary of the worker whose salary and raise rate is entered on Python?

```
newsalary = 0
salary = input("enter new salary : ")
raise = input("salary raise rate(%) : ")
newsalary = int(salary)+(int(salary)*int(raise)/100)
print("increased salary :",newsalary)

```
24. How to calculate the area and circumference of the circle whose radius is entered using the function on Python?

```
import math
 
def find_Diameter(radius):
    return 2 * radius
 
def find_Circumference(radius):
    return 2 * math.pi * radius
 
def find_Area(radius):
    return math.pi * radius * radius
 
r = float(input(' Please Enter the radius of a circle: '))
 
diameter = find_Diameter(r)
circumference = find_Circumference(r)
area = find_Area(r)
 
print("\n Diameter Of a Circle = %.2f" %diameter)
print(" Circumference Of a Circle = %.2f" %circumference)
print(" Area Of a Circle = %.2f" %area)

```
25. How to calculate the area of the rectangle, whose width and height are entered using the function on Python?

```
def areaRectangle(a, b): 
    return (a * b) 
  
def perimeterRectangle(a, b): 
    return (2 * (a + b)) 
a = 5; 
b = 6; print ("Area = ", areaRectangle(a, b))

print ("Perimeter = ", perimeterRectangle(a, b))

```
26. Making a Number Guessing Game with Python
```
import random
import math
# Taking Inputs
lower = int(input("Enter Lower bound:- "))
 
# Taking Inputs
upper = int(input("Enter Upper bound:- "))
 
# generating random number between
# the lower and upper
x = random.randint(lower, upper)
print("\n\tYou've only ", 
       round(math.log(upper - lower + 1, 2)),
      " chances to guess the integer!\n")
 
# Initializing the number of guesses.
count = 0
 
# for calculation of minimum number of
# guesses depends upon range
while count < math.log(upper - lower + 1, 2):
    count += 1
 
    # taking guessing number as input
    guess = int(input("Guess a number:- "))
 
    # Condition testing
    if x == guess:
        print("Congratulations you did it in ",
              count, " try")
        # Once guessed, loop will break
        break
    elif x > guess:
        print("You guessed too small!")
    elif x < guess:
        print("You Guessed too high!")
 
# If Guessing is more than required guesses,
# shows this output.
if count >= math.log(upper - lower + 1, 2):
    print("\nThe number is %d" % x)
    print("\tBetter Luck Next time!")
```
27. How to find out what day of the year a given date is on Python?
```
import datetime

date=str(input('Enter the date(for example:09 02 2019):'))
day_name= ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday','Sunday']
day = datetime.datetime.strptime(date, '%d %m %Y').weekday()
print(day_name[day])
```
28. How to find missing numbers in a sorted list range on Python?
```
def find_missing(lst): 
    return [x for x in range(lst[0], lst[-1]+1)  
                               if x not in lst] 
  
# Driver code 
lst = [1, 2, 4, 6, 7, 9, 10] 
print(find_missing(lst))
Output:
[3, 5, 8]

```
29. How to check if there is a specified character in a string on Python?

```
char_list = ["a", "b" ,"c"]
string = "abcd"
matched_list = [characters in char_list for characters in string]
print(matched_list)
OUTPUT
[True, True, True, False]
string_contains_chars = all(matched_list)
print(string_contains_chars)

```
30. How to find the average of odd and even averages of whole numbers on Python?
```
total = 0
evenSums = 0
oddSums = 0
done = False
while(not done):
    user_in = input("Give me an integer or type 'done' to be done.")
    if( user_in.lower() == "done"):
        done = True
    else:
        # assuming they've typed in an integer
        total += int(user_in)
        if user_in % 2 == 0:
            evenSums += user_in
            evenAverage = evenSums / user_in
        else:
            oddSums += user_in
            oddAverage = oddSums / user_in
print(total)
print("Even Average: " + str(evenAverage))
print("Odd Average: " + str(oddAverage))
```
31. How to put records from the database on Python?

```
import pymysql.cursors
# Database connection sentence
connection = pymysql.connect(host='localhost',
                             user='root',
                             password='',
                             db='students',
                             charset='utf8mb4',
                             cursorclass=pymysql.cursors.DictCursor)
try:
    with connection.cursor() as cursor:
        # single line reading
        sql = "SELECT `id`, `firstname`,`lastname` FROM `users`"
        cursor.execute(sql)
        for row in cursor.fetchall():
            #read all lines
            firstname = str(row["firstname"])
            lastname = str(row["lastname"])
            #print on screen
             print("firstname : " + firstname)
             print("lastname : " + lastname)
finally:
        connection.close()

```
32. How to Use Tkinter Form on Python?

```
from tkinter import *
window = Tk()
# add widgets here

window.title('Hello Python')
window.geometry("300x200+10+20")
window.mainloop()
```
33. How to Create Python Form Entry on Python?
```
from tkinter import *
from tkinter import messagebox
window = Tk()
window.title("mrhuseyin.medium.com")
window.geometry("400x300")
#plotting grid forms
application = Frame(window)
application.grid()
L1 = Label(uygulama, text="Enter your name")
L1.grid(padx=110, pady=10)
E1 = Entry(application, bd =2)
E1.grid(padx=110, pady=3)
#draw form
window.mainloop()
```
34. How to create Python Tkinter ListBox on Python?
```
from tkinter import *
 
from tkinter import messagebox
 
window = Tk()
 
window.title("mrhuseyin.medium.com")
window.geometry("400x300")
 
#grid form çizdirme
application = Frame(window)
application.grid()
 
 
Lb1 = Listbox(application)
Lb1.insert(1, "Python")
Lb1.insert(2, "C#")
Lb1.insert(3, "JAVA")
Lb1.insert(4, "JAVASCRIPT")
Lb1.grid(padx=110, pady=10)
 
#draw form
pencere.mainloop()
```
35. How to make a simple registration form using Python Tkinter on Python?
```
# import openpyxl and tkinter modules 
from openpyxl import *
from tkinter import *
  
# globally declare wb and sheet variable 
  
# opening the existing excel file 
wb = load_workbook('C:\\Users\\Admin\\Desktop\\excel.xlsx') 
  
# create the sheet object 
sheet = wb.active 
  
  
def excel(): 
      
    # resize the width of columns in 
    # excel spreadsheet 
    sheet.column_dimensions['A'].width = 30
    sheet.column_dimensions['B'].width = 10
    sheet.column_dimensions['C'].width = 10
    sheet.column_dimensions['D'].width = 20
    sheet.column_dimensions['E'].width = 20
    sheet.column_dimensions['F'].width = 40
    sheet.column_dimensions['G'].width = 50
  
    # write given data to an excel spreadsheet 
    # at particular location 
    sheet.cell(row=1, column=1).value = "Name"
    sheet.cell(row=1, column=2).value = "Course"
    sheet.cell(row=1, column=3).value = "Semester"
    sheet.cell(row=1, column=4).value = "Form Number"
    sheet.cell(row=1, column=5).value = "Contact Number"
    sheet.cell(row=1, column=6).value = "Email id"
    sheet.cell(row=1, column=7).value = "Address"
  
  
# Function to set focus (cursor) 
def focus1(event): 
    # set focus on the course_field box 
    course_field.focus_set() 
  
  
# Function to set focus 
def focus2(event): 
    # set focus on the sem_field box 
    sem_field.focus_set() 
  
  
# Function to set focus 
def focus3(event): 
    # set focus on the form_no_field box 
    form_no_field.focus_set() 
  
  
# Function to set focus 
def focus4(event): 
    # set focus on the contact_no_field box 
    contact_no_field.focus_set() 
  
  
# Function to set focus 
def focus5(event): 
    # set focus on the email_id_field box 
    email_id_field.focus_set() 
  
  
# Function to set focus 
def focus6(event): 
    # set focus on the address_field box 
    address_field.focus_set() 
  
  
# Function for clearing the 
# contents of text entry boxes 
def clear(): 
      
    # clear the content of text entry box 
    name_field.delete(0, END) 
    course_field.delete(0, END) 
    sem_field.delete(0, END) 
    form_no_field.delete(0, END) 
    contact_no_field.delete(0, END) 
    email_id_field.delete(0, END) 
    address_field.delete(0, END) 
  
  
# Function to take data from GUI  
# window and write to an excel file 
def insert(): 
      
    # if user not fill any entry 
    # then print "empty input" 
    if (name_field.get() == "" and
        course_field.get() == "" and
        sem_field.get() == "" and
        form_no_field.get() == "" and
        contact_no_field.get() == "" and
        email_id_field.get() == "" and
        address_field.get() == ""): 
              
        print("empty input") 
  
    else: 
  
        # assigning the max row and max column 
        # value upto which data is written 
        # in an excel sheet to the variable 
        current_row = sheet.max_row 
        current_column = sheet.max_column 
  
        # get method returns current text 
        # as string which we write into 
        # excel spreadsheet at particular location 
        sheet.cell(row=current_row + 1, column=1).value = name_field.get() 
        sheet.cell(row=current_row + 1, column=2).value = course_field.get() 
        sheet.cell(row=current_row + 1, column=3).value = sem_field.get() 
        sheet.cell(row=current_row + 1, column=4).value = form_no_field.get() 
        sheet.cell(row=current_row + 1, column=5).value = contact_no_field.get() 
        sheet.cell(row=current_row + 1, column=6).value = email_id_field.get() 
        sheet.cell(row=current_row + 1, column=7).value = address_field.get() 
  
        # save the file 
        wb.save('C:\\Users\\Admin\\Desktop\\excel.xlsx') 
  
        # set focus on the name_field box 
        name_field.focus_set() 
  
        # call the clear() function 
        clear() 
  
  
# Driver code 
if __name__ == "__main__": 
      
    # create a GUI window 
    root = Tk() 
  
    # set the background colour of GUI window 
    root.configure(background='light green') 
  
    # set the title of GUI window 
    root.title("registration form") 
  
    # set the configuration of GUI window 
    root.geometry("500x300") 
  
    excel() 
  
    # create a Form label 
    heading = Label(root, text="Form", bg="light green") 
  
    # create a Name label 
    name = Label(root, text="Name", bg="light green") 
  
    # create a Course label 
    course = Label(root, text="Course", bg="light green") 
  
    # create a Semester label 
    sem = Label(root, text="Semester", bg="light green") 
  
    # create a Form No. lable 
    form_no = Label(root, text="Form No.", bg="light green") 
  
    # create a Contact No. label 
    contact_no = Label(root, text="Contact No.", bg="light green") 
  
    # create a Email id label 
    email_id = Label(root, text="Email id", bg="light green") 
  
    # create a address label 
    address = Label(root, text="Address", bg="light green") 
  
    # grid method is used for placing 
    # the widgets at respective positions 
    # in table like structure . 
    heading.grid(row=0, column=1) 
    name.grid(row=1, column=0) 
    course.grid(row=2, column=0) 
    sem.grid(row=3, column=0) 
    form_no.grid(row=4, column=0) 
    contact_no.grid(row=5, column=0) 
    email_id.grid(row=6, column=0) 
    address.grid(row=7, column=0) 
  
    # create a text entry box 
    # for typing the information 
    name_field = Entry(root) 
    course_field = Entry(root) 
    sem_field = Entry(root) 
    form_no_field = Entry(root) 
    contact_no_field = Entry(root) 
    email_id_field = Entry(root) 
    address_field = Entry(root) 
  
    # bind method of widget is used for 
    # the binding the function with the events 
  
    # whenever the enter key is pressed 
    # then call the focus1 function 
    name_field.bind("<Return>", focus1) 
  
    # whenever the enter key is pressed 
    # then call the focus2 function 
    course_field.bind("<Return>", focus2) 
  
    # whenever the enter key is pressed 
    # then call the focus3 function 
    sem_field.bind("<Return>", focus3) 
  
    # whenever the enter key is pressed 
    # then call the focus4 function 
    form_no_field.bind("<Return>", focus4) 
  
    # whenever the enter key is pressed 
    # then call the focus5 function 
    contact_no_field.bind("<Return>", focus5) 
  
    # whenever the enter key is pressed 
    # then call the focus6 function 
    email_id_field.bind("<Return>", focus6) 
  
    # grid method is used for placing 
    # the widgets at respective positions 
    # in table like structure . 
    name_field.grid(row=1, column=1, ipadx="100") 
    course_field.grid(row=2, column=1, ipadx="100") 
    sem_field.grid(row=3, column=1, ipadx="100") 
    form_no_field.grid(row=4, column=1, ipadx="100") 
    contact_no_field.grid(row=5, column=1, ipadx="100") 
    email_id_field.grid(row=6, column=1, ipadx="100") 
    address_field.grid(row=7, column=1, ipadx="100") 
  
    # call excel function 
    excel() 
  
    # create a Submit Button and place into the root window 
    submit = Button(root, text="Submit", fg="Black", 
                            bg="Red", command=insert) 
    submit.grid(row=8, column=1) 
  
    # start the GUI 
    root.mainloop()
```
36. How to make a game that guesses the number the user holds on Python?
```
from random import randint
 
rand = randint(1, 100)
counter = 0
 
while True:
    counter+=1
    num=int(input("Enter values between 1 and 100 (0 exit):"))
    if(num==0):
        print("You canceled the game.")
        break
    elif num < rand:
        print("Enter a Higher Number.")
        continue
    elif num > rand:
        print("Enter a Lower Number.")
        continue
    else:
        print("Randomly selected number {0}!".format(rand))
        print("Your guess number {0}".format(counter))
```
37. How to make a list of your favorite fruits and print them on the screen on Python?
```
favorite_fruits = ['apples', 'erics', 'oranges']
print("My favourite fruits {}".format(favorite_fruits))
```
38. How to print “the number of pi in order, the equivalent of the inch unit in cm, the abbreviation of microprocessors, the name of the operating system you are using” on Python?
```
list=[3.14,2.54,"CPU","WINDOWS 10"]
 
print(list)
Output:
[3.14, 2.54, 'CPU', 'WINDOWS 10']
```
39. How to make a list of the days of the week beginning with Monday and ending with Friday. Also, how to print the element of the list you have created with an index of 4 on the screen on Python?
```
weekdays=["Monday","Tuesday","Wednesday","Thursday","Friday"]
print(weekdays[4])
output
Thursday
```
40. How to change the list from 3,1,2 values to 1,1,2 respectively on Python?
```
list=[3,1,2]
 
list[0]=1
list[1]=1
list[2]=2
 
print(list)
output
[1, 1, 2]
```
41. How to make a list of the week’s names and check if some days are on the list on Python?
```
weekdays=["Monday","Tuesday","Wednesday","Thursday","Friday"]
 
print("Friday" in weekdays)
print("Saturday" in weekdays)
output
true
false
```
42. How to print even numbers in a list on Python?
```
list1 = [10, 21, 4, 45, 66, 93] 
  
for num in list1: 
      
    # checking condition 
    if num % 2 == 0: 
       print(num, end = " ")
```
43. Create a list named numbers consisting of 3–18 numbers. Combine the list created with the list of “numbers2 = [21,22,23,24,25]”, then print the numbers divided by 4 on the screen.
```
numbers = [3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18]
numbers2 = [21,22,23,24,25]
combine = numbers + numbers2
 
for number in combine:
 if sayi%4==0:
  print(number)
```
44. How to write the code with the screen output as below with the while loop on Python?
```
1 . class
2 . class
3 . class
4 . class
5 . class
6 . class
7 . class
8 . class
9 . class
10 . class
11 . class
12 . class
```
```
i = 1
while i <= 12:
  print(" {}. class".format(i))
  i += 1
```
45. How to sum the digits of the number the user entered on Python?
```
number = input("enter a number: ")
sum=0
for numberofdigit in number:
  sum += int(numberofdigit)
 
print("the sum of the digits of the number:",sum)
```
46. How to multiply the digits of the number entered by the user (except zero) on Python?
```
number = input("enter an number: ")
carpim=1
for digitofnumber in str(numaber):
  if int(digitofnumber) != 0:
    multiplication*= int(digitofnumber)
print("digits of the number: ",multiplication)
```
47. How to print the programmer’s name on the screen using the “for loop” on Python?
```
text = input("enter a name: ")
 
for i in range(10):
  print(text)
```
48. How to print the programmer’s name on the screen using the “while loop” on Python?

```
text = input("enter a name: ")
 
i=0
while i<10:
  i+=1
  print(text)

```
49. How to find the mean using “sum() and len()” on Python?
```
list=[35,48,52,57,68,84]
 
total = sum(list)
piece = len(list)
print(total/piece)
```
50. How to find the sum of numbers until 0 is entered on the keyboard on Python?
```
total=0
while True:
  num = float(input("enter a number: "))
  if numr ==0:
    break
  total+=num
print("The sum of the numbers: ",total)
```
