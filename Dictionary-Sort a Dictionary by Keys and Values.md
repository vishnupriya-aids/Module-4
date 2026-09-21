# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
d = eval(input("Enter dictionary: ")) sorted_keys = dict(sorted(d.items())) sorted_values = dict(sorted(d.items(), key=lambda item: item[1])) print("Sorted by keys:", sorted_keys) print("Sorted by values:", sorted_values)

## Sample Output
Enter dictionary: {'b': 'banana', 'a': 'apple', 'c': 'cherry'} Sorted by keys: {'a': 'apple', 'b': 'banana', 'c': 'cherry'} Sorted by values: {'a': 'apple', 'b': 'banana', 'c': 'cherry'}

## Result
The program executed successfully and sorted the dictionary by keys and values in alphabetical order using built-in sorting functions.

