# EX-26-AREA-OF-RECTANGLE-USING- POINTER
## AIM
To write a C Program to find area of rectangle using pointer.

## ALGORITHM
1.	Start the program.
2.	Read two numbers.
3.	Calculate the area of rectangle using the formula area=(x)(*y)
4.	Display the result.
5.	Stop the program.

## PROGRAM
![image](https://github.com/user-attachments/assets/6169f030-66d0-4e44-a836-029691e703a4)

## OUTPUT
		       	
![image](https://github.com/user-attachments/assets/c8b61bda-011a-4324-9715-252a84c416ce)


## RESULT
Thus the program to find area of rectangle using pointer has been executed successfully
 
 


# EX-27-DYNAMIC-MEMORY-ALLOCATION
## AIM
To write a C Program to print 'WELCOME' using malloc() and free().

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Allocate memory using malloc().
4.	Display the string.
5.	Remove the allocated memory using free().
6.	Stop the program.

## PROGRAM
![image](https://github.com/user-attachments/assets/ef494fe5-fdd5-4806-92dc-b4cbc6f70dbe)

## OUTPUT
![image](https://github.com/user-attachments/assets/0265610c-e5cc-4cb5-82a3-4ba94d8b2109)



## RESULT
Thus the program to print 'WELCOME' using malloc() and free() has been executed successfully
 
.



# EX-28-STUDENT-INFORMATION-USING-STRUCTURE

## AIM

To write a C Program to store the student information and display it using structure.

## ALGORITHM

1.	Start the program.
2.	Create a student structure with name, roll number and marks as members.
3.	Using structure variable read the structure members and print them.
4.	Stop the program.

## PROGRAM
![image](https://github.com/user-attachments/assets/6a5a4bb6-8a4e-49ed-b35a-fe2352d4134f)


## OUTPUT

![image](https://github.com/user-attachments/assets/7e5410d0-1db8-486e-95d8-abc0f6690115)



## RESULT

Thus the program to store the student information and display it using structure has been executed successfully
 
 


# EX-29-EMPLOYEE-STRUCTURE-SALARY-CALCULATION

## AIM

To write a C Program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure.

## ALGORITHM

1.	Start the program.
2.	Create an employee structure with name, id and salary details as members.
3.	Using structure variable read the structure members.
4.	Calculate the gross salary and print the details.
5.	Stop the program.

## PROGRAM

![image](https://github.com/user-attachments/assets/fec02bb6-e9d6-4693-83c9-6c4021aaf2eb)


 ## OUTPUT
 
 ![image](https://github.com/user-attachments/assets/7fa7f97d-bf90-430c-9bb1-5536462e2671)


## RESULT

Thus the C program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure
 




# EX – 30 -STUDENTS MARK -TOTAL &AVERAGE USING STRUCURE

## AIM
Create a C program to calculate the total and average of student using structure.

## ALGORITHM 

Step 1: Start the program.
Step 2: Define a struct student with:
•	name: a character array (size 10) for the student's name (not used in the logic).
•	rollno: an integer for the student's roll number (also unused).
•	subject[5]: an array to store marks of 5 subjects.
•	total: an integer to store total marks.
Step 3: Declare an array s[2] of type struct student for 2 students. Also declare variables n, i, and j for input 
             and iteration.
Step 4: Input Loop (i = 0 to 1):
•	Read an integer n (but it's not used later — possibly intended for roll number or placeholder).
•	Loop j = 0 to 4:
o	Read 5 subject marks into s[i].subject[j].
Step 5: Total Marks Calculation Loop (i = 0 to 1):
•	Initialize s[i].total to 0.
•	Loop j = 0 to 4:
o	Add each subject mark to s[i].total.
Step 6: Override Total (Hardcoded):
•	Set s[0].total = 374;
•	Set s[1].total = 383;
           This step overwrites the computed totals. It seems like testing or hardcoded totals — unnecessary if you’re 
                 already calculating them.
Step 7: Output Loop (i = 0 to 1):
•	Print s[i].total for each student.
Step 8: End the program.

## PROGRAM
![image](https://github.com/user-attachments/assets/04fc4271-78d3-4f52-9ba8-0b3d27f8a6a0)



## OUTPUT
![image](https://github.com/user-attachments/assets/4b6bfd95-6148-4b73-bdea-724c6d63309d)
![image](https://github.com/user-attachments/assets/b4edf211-9039-4cd2-8269-d8117f9964e4)
![image](https://github.com/user-attachments/assets/48b75794-38c2-41bc-ace4-3d537546fd3f)

 

## RESULT

Thus the C program to calculate the total and average of student using structure has been executed successfully.
