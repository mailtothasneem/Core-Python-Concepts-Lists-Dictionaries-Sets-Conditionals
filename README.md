# Core-Python-Concepts-Lists-Dictionaries-Sets-Conditionals
Python assignment demonstrating lists, dictionaries, sets, and conditionals in Jupyter Notebook. Practice project on Python data structures and decision-making (lists, dicts, sets, if‑else)."

---

✨ # 📘 Python Assignment – Lists, Dictionaries, Sets & Conditionals

## 📖 Overview
This project demonstrates Python programming concepts using **core data structures** and **conditional statements**.  
It covers:
- List creation, modification, and access operations  
- Dictionary creation and manipulation using key-value pairs  
- Set properties and operations (uniqueness, union, intersection)  
- Decision-making using conditional statements (`if`, `elif`, `else`)  

---

## 📝 Problem Statement
As a Python learner, the objective of this assignment is to develop a strong understanding of:
- Lists (creation, modification, access)  
- Dictionaries (key-value mapping and updates)  
- Sets (unique elements, union, intersection)  
- Conditional statements for decision-making  


---

## 🔹 Tasks

### 1. Lists (Creation, Modification, and Access)

#### a. List Creation
- Create `age_list` with five integer elements → `[24, 25, 27, 28, 29]`  
- Create `name_list` with five string elements → `['Thasneem','Uma','Priya','Elakkiya','Salma']`

#### b. List Operations / Modifications
- Append `"Yazhini"` to `name_list`  
- Insert `26` at index `2` in `age_list`  
- Remove `"Yazhini"` from `name_list`  
- Pop the last element from `age_list`  
- Extend `age_list` with `[31, 30, 32]`  
- Sort `age_list` in descending order  
- Find **max age**, **min age**, and **sum of ages**  

#### c. Accessing List Elements
- Print the first element of `name_list`  
- Print the last element of `name_list`  
- Print elements from index `2` to `4` in `name_list`  
- Print elements of `name_list` in reverse order

  ### Output

`First element of name_list: Thasneem`
`Last element of name_list: Priya`
`Elements from index 2 to 4: ['Kaviya', 'Meena', 'Priya']`
`Reverse order: ['Priya', 'Meena', 'Kaviya', 'Anu', 'Thasneem']`


---

### 2. Dictionaries (Creation, Modification, and Access)
- Create `student_marks` dictionary mapping five students to marks (0–100 scale)  
- Access and print the mark of a specific student  
- Add new student `"Janani"` with mark `80`  
- Update the mark of one student to `82`  
- Use `.keys()`, `.values()`, `.items()` to print keys, values, and key-value pairs  

---

### 3. Sets (Operations)
- Create `my_set = ['a','e','i','o','u','a','a','i']`  
  - Analyze output (duplicates removed, only unique values stored)  
- Attempt to access `my_set[4]` → Error (sets are unordered, indexing not allowed)  
- Create two sets:  
  - `set1 = {1, 3, 5, 7, 9}`  
  - `set2 = {2, 3, 5, 8, 10}`
  output
-` my_set output: {'a', 'e', 'i', 'o', 'u'}
Error: 'set' object is not subscriptable`

  

---

### 4. Conditional Statements (IF, ELIF, ELSE)
**Performance Category Program**  
- Prompt user for input score (0–10)  
- Categorize performance:  
  - Above Average → score > 7  
  - Average → score between 4 and 7 (inclusive)  
  - Below Average → score < 4  


**Sample Output:**
```text
Enter your score (0 to 10): 7
Average: Good effort! Keep practicing, there's room for improvement.

Max age: 32
Min age: 24
Sum of ages: 196

Student marks keys: dict_keys(['Arun', 'Bala', 'Kaviya', 'Meena', 'Priya', 'Janani'])
Student marks values: dict_values([75, 68, 90, 82, 60, 80])
Student marks items: dict_items([('Arun', 75), ('Bala', 68), ('Kaviya', 90), ('Meena', 82), ('Priya', 60), ('Janani', 80)])

Union: {1, 2, 3, 5, 7, 8, 9, 10}
Intersection: {3, 5}

````
Created By 
L Thasneem
AI-Driven Data Analytics

