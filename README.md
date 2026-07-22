# Python Data Structures – List, Tuple, Set, Dictionary

This notebook covers the four core Python data structures, their properties, and the built-in methods used to work with them.

## 📌 List

A **list** is an ordered, mutable (changeable) collection of items that can hold elements of different data types. Lists allow duplicate values and maintain the order in which elements are inserted.

### List Methods Covered
- **Indexing** – Accessing elements using their position (e.g., first element, last element).
- **len()** – Returns the number of elements in a list.
- **append()** – Adds a single element to the end of a list.
- **insert()** – Adds an element at a specific index/position.
- **extend()** – Adds all elements of one list to another (combines lists).
- **remove()** – Deletes the first occurrence of a specified value.
- **pop()** – Removes and returns an element at a given index (removes the last element if no index is given).
- **sort()** – Sorts the list in place in ascending order (can be reversed using `reverse=True`).
- **sorted()** – Returns a new sorted list without modifying the original list.
- **reverse()** – Reverses the order of elements in the list.
- **index()** – Returns the position of the first occurrence of a value.
- **count()** – Returns how many times a value appears in the list.

---

## 📌 Tuple

A **tuple** is an ordered, **immutable** (unchangeable) collection of items. Once created, elements cannot be added, removed, or modified. Tuples can hold mixed data types and allow duplicate values.

### Tuple Concepts Covered
- **Creating a tuple** – Defining a tuple using parentheses `()`.
- **Single-element tuple** – Requires a trailing comma to be recognized as a tuple.
- **Indexing** – Accessing elements by position (first, last, third element, etc.).
- **Slicing** – Extracting a portion of a tuple (e.g., first three elements, last two elements).
- **Reversing using slicing** – Using step `-1` to reverse the tuple.
- **count()** – Counts occurrences of a specific value.
- **index()** – Finds the position of a specific value.
- **Type conversion** – Converting a tuple to a list (to allow modification) and converting a list back to a tuple.

---

## 📌 Set

A **set** is an unordered collection of **unique** items — duplicate values are automatically removed. Sets are mutable but do not support indexing since they have no defined order.

### Set Methods Covered
- **Creating a set** – Defining a set using curly braces `{}`.
- **Duplicate handling** – Sets automatically eliminate duplicate values.
- **Empty set** – Created using `set()` (not `{}`, which creates a dictionary).
- **add()** – Adds a single element to a set.
- **update()** – Adds multiple elements to a set at once.
- **remove()** – Deletes a specified element (raises an error if not found).
- **discard()** – Deletes a specified element (does not raise an error if not found).
- **pop()** – Removes and returns a random element from the set.
- **len()** – Returns the number of elements in a set.
- **union()** – Combines all unique elements from two sets.
- **intersection()** – Returns elements common to both sets.
- **difference()** – Returns elements present in one set but not the other.
- **symmetric_difference()** – Returns elements that are in either set, but not in both.

---

## 📌 Dictionary

A **dictionary** is an unordered (insertion-ordered in modern Python) collection of **key-value pairs**. Each key must be unique and is used to access its corresponding value.

### Dictionary Methods Covered
- **Creating a dictionary** – Defining key-value pairs using curly braces `{}`.
- **Accessing values** – Retrieving a value using its associated key.
- **Adding a key-value pair** – Inserting a new key with its value.
- **Updating a value** – Modifying the value of an existing key.
- **pop()** – Removes a specified key and returns its value.
- **del keyword** – Deletes a specified key-value pair.
- **len()** – Returns the number of key-value pairs.
- **in keyword** – Checks whether a key exists in the dictionary.
- **get()** – Safely retrieves the value of a key without raising an error if the key doesn't exist.
- **keys()** – Returns all the keys in the dictionary.
- **values()** – Returns all the values in the dictionary.
- **items()** – Returns all key-value pairs as pairs (tuples).

---

## Summary Table

| Data Structure | Ordered | Mutable | Duplicates Allowed | Indexed |
|---|---|---|---|---|
| List | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes |
| Tuple | ✅ Yes | ❌ No | ✅ Yes | ✅ Yes |
| Set | ❌ No | ✅ Yes | ❌ No | ❌ No |
| Dictionary | ✅ Yes (insertion order) | ✅ Yes | ❌ No (keys unique) | ✅ Yes (by key) |
# Conditions in Python

This notebook covers Python's conditional statements, which allow a program to make decisions and execute different blocks of code depending on whether certain conditions are `True` or `False`.

---

## Simple `if`
Executes a block of code only if a given condition evaluates to `True`. If the condition is `False`, the block is simply skipped and nothing happens.

## `if-else`
Provides two possible paths of execution — one block runs if the condition is `True`, and another (`else`) block runs if the condition is `False`.

## `if-elif-else`
Used when there are multiple conditions to check in sequence. Python evaluates each `elif` condition in order and executes the block for the first one that is `True`. If none of the conditions match, the `else` block runs.

## Nested `if`
An `if` statement placed inside another `if` (or `else`) block. It is used to check a secondary condition only after the first (outer) condition has already been satisfied.

## Logical Operators
Operators (`and`, `or`, `not`) used to combine multiple conditions into a single expression, allowing a decision to be based on more than one criterion at the same time.

## Shorthand / Ternary Operator
A one-line way of writing simple `if-else` statements, expressed in the form:
`value_if_true if condition else value_if_false`.

## User-Input Based Conditions
Programs that take input from the user at runtime and apply conditional logic to that input to produce an appropriate output.

## Extra / Special Applications
Real-world examples that apply conditional logic together, including:
- **Leap Year check** – determining whether a year is a leap year using divisibility rules.
- **Century Year check** – checking whether a year is an exact multiple of 100.
- **Character type check** – identifying whether a character is uppercase, lowercase, a digit, or a special symbol.
- **Electricity Bill calculation** – applying different billing rates based on unit-consumption slabs.
- **Simple Calculator** – performing arithmetic operations based on an operator entered by the user.
- **Result/Grading system** – calculating total marks, percentage, and grade from multiple subject scores using conditions.
