# Data-Structures---List-Dictionary-Set-Conditional-Statements-
This repository contains Python programs demonstrating data structures such as Lists, Dictionaries, and Sets, along with conditional statements (if, elif, and else). It includes practical examples and exercises to understand data manipulation, set operations, and decision-making in Python.

Python Data Structures & Conditional Statements

📌 Project Overview
A beginner-friendly Python assignment covering fundamental programming concepts.
Demonstrates Lists, Dictionaries, Sets, and Conditional Statements.
Includes practical examples of data creation, modification, access, and manipulation.
Helps develop logical thinking and problem-solving skills.

🎯 Objectives
Understand Python's built-in data structures.
Learn to add, remove, update, and access elements.
Explore set operations such as union and intersection.
Practice decision-making using if, elif, and else.
Understand common Python errors and how to resolve them.

📋 1. Lists
A list stores multiple elements in a single variable.
Lists are ordered, mutable, and allow duplicate values.
Example:

age_list = [24, 25, 26, 27, 28, 29]

age_list.append(30)
age_list.insert(2, 26)
age_list.extend([31, 30, 32])

print(age_list)
Important list methods:

append() – Adds one element.
insert() – Adds an element at a specific index.
remove() – Removes a specified element.
pop() – Removes an element by index or removes the last element by default.
extend() – Adds multiple elements from an iterable.
sort() – Sorts the list.
max(), min(), sum() – Find the maximum, minimum, and total.
List access examples:

name_list = ['Naveen', 'Angel', 'Hepzi', 'Edward', 'Sheeba']

print(name_list[0])     # First element
print(name_list[-1])    # Last element
print(name_list[2:5])   # Elements at indexes 2 to 4
print(name_list[::-1])  # Reverse order

📚 2. Dictionaries
A dictionary stores information as key-value pairs.
Keys are unique, and values can be accessed using their keys.
Dictionaries are useful for storing student details and marks.
Example:

student_marks = {
    'Jerin': 100,
    'Jerlin': 90,
    'Jerusha': 82,
    'sharon': 70,
    'Glinda': 95
}

student_marks['Janani'] = 80
student_marks['Jerlin'] = 82

print(student_marks.keys())
print(student_marks.values())
print(student_marks.items())
Important dictionary methods:

keys() – Returns all keys.
values() – Returns all values.
items() – Returns key-value pairs.

🔠 3. Sets
A set stores unique elements and automatically removes duplicates.
Sets are unordered and do not support indexing.
They are useful for comparing collections and removing duplicates.
Example:

my_set = set(['a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'])
print(my_set)
Possible output:

{'a', 'e', 'i', 'o', 'u'}
Set operations:

set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}

print(set1.union(set2))
print(set1.intersection(set2))
union() – Combines unique elements from both sets.
intersection() – Returns elements common to both sets.
my_set[4] – Raises a TypeError because sets do not support indexing.

⚙️ 4. Conditional Statements
Conditional statements allow a program to make decisions based on conditions.
if checks the first condition.
elif checks another condition when the previous one is false.
else executes when all preceding conditions are false.

Example: Performance Category Program

score = int(input("Enter your score (0 to 10): "))

if score > 7:
    print("Above Average: Excellent work! Keep it up!")
elif score >= 4:
    print("Average: Good effort! Keep practicing, there's room for improvement.")
else:
    print("Below Average: Need to improve your performance; consistent practice will lead to better results.")

Sample output:

Enter your score (0 to 10): 7
Average: Good effort! Keep practicing, there's room for improvement.
Scores 8–10 → Above Average.
Scores 4–7 → Average.
Scores 0–3 → Below Average.
Note: This example assumes the user enters a valid integer between 0 and 10.

🚀 Learning Outcomes
Gain practical experience with Python lists, dictionaries, and sets.
Understand indexing, slicing, and collection methods.
Learn how to organize and manipulate data efficiently.
Apply conditional logic to real-world programming problems.
Improve coding confidence through hands-on exercises.
🛠️ Technologies Used
Python 3
Jupyter Notebook
