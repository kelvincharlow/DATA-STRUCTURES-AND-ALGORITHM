# DATA-STRUCTURES-AND-ALGORITHM
KELVIN MUSYOKI
SCT212-0712/2022
ASSIGNMENT 1

QUIZ1 ARRAYS 
      Question 1
     
      Function eliminate_Duplicates
Takes an array (arr) and its size (k) as parameters
Uses two pointers (x and y) to go through the array
If the current element (arr[y]) is different from the previous unique element it updates the array in-place and x is incremented
Returns the new length of the array with unique elements

    main Function
Initializes an array nums with duplicate elements
Calculates the size of the array (k)
Calls eliminate_Duplicates to remove duplicates in-place and get the new length.
Prints the new length of the array
Prints the array with unique elements

  Question 2
    
    Function array_Rotation
>Takes an array of numbers (numbers), its length (len), and the number of positions to rotate (k) as parameters
>Adjusts k to avoid unnecessary rotations by taking the remainder when divided by the length of the array
>Reverses the entire array using two pointers (start and end)
>Reverses the first k elements
>Reverses the remaining elements in the array

    main Function
Initializes an array numbers and specifies the rotation positions (k = 2)
Calls array_Rotation to perform the right rotation 
Prints the rotated array

    Output
Displays the array after performing a right rotation by 2 positions

  Question 3
  
    Function check_For_Duplicates
Takes an array of integers (arr) and its size (n) as parameters
Uses two nested loops to compare each pair of elements in the array
If it finds two elements that are equal it returns true indicating that duplicates are present
If no duplicates are found after checking all pairs it returns false

    main Function
Initializes an array nums
Calculates the size of the array (n)
Calls check_For_Duplicates to determine if there are any duplicate elements
Prints "True" if duplicates are found and "False" if not the case

  Question 4
  
    Function Definition (find_Single_Number)
This function looks for a single unique number in an array
It takes two parameters nums (the array) and len (the length of the array)

    Variables Initialization
int single_Number = -1 Initializes a variable to store the single number It starts with -1 as a placeholder

    Nested Loop (Checking for Duplicates)
Two nested loops are used to compare each element of the array with every other element
If an element is found to be the same as another element at a different position it sets (has_Duplicate) to true and breaks out of the inner loop

    Checking for No Duplicates
If (has_Duplicate) remains false after the inner loop it means the current element doesn't have any duplicates in the array
In that case the current element is considered the single number and it is stored in the single_Number variable The loop breaks 
The function returns the value of single_Number which is either the identified single number or -1 if no single 

    Main Function
Initializes an array nums with values and calculates its length (len)
Calls the find_Single_Number function with the array and its length
Prints the result

LABTASK 1
   
  Task 1
    
    Function Definitions (summation and maximum)
These functions calculate the sum and find the maximum element in an array respectively

    Main Function
User inputs the number of elements (n) to be stored in the array
An array (nums) is dynamically allocated with size n

    User Input
User inputs the integers into the dynamically allocated array

    Function Calls and Output
The summation and maximum functions are called with the dynamically allocated array and its size
The calculated sum and maximum element are displayed

    Memory Deallocation
The dynamically allocated array (nums) is deallocated using delete[] nums to avoid memory leaks

  Task 2
 
    Struct Definitions
Course Represents information about a course including a course code and name
Grade Represents the grade of a student consisting of a numerical mark and a corresponding letter grade
Student Represents a student holding details such as registration number name age course information and grade

    Function Definition (calculateGrade)
Takes a numerical mark as input and returns the corresponding letter grade 

    Main Function
Creates an instance of the Student structure named new_student
Calls calculateGrade to determine the initial letter grade
Edits the students name and updates the grade with a new mark recalculating the letter grade
Displays the details of the student including registration number name age course information mark and letter grade

  Task 3
    
    Classes
Course Represents information about a course, such as its code and name
Grade Represents a student's grade, consisting of a numerical mark and a letter grade based on a grading system
Student Represents a student, with details like registration number, name, age, the course they are enrolled in, and their grades. The add_mark function calculates and sets the grade based on the provided mark
School Manages an array of students allowing the addition of students and editing of their details

    Main Function
Adds the student to the School
Edits the student's details (name, age, and mark) through the edit_student_details function

  Task 4
