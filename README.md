# 13_dict_methods

A complete Python practice notebook demonstrating dictionary methods, key–value operations, looping techniques, and practical examples.  
Useful for beginners learning Python dictionaries and for reference in projects.

---

## 📌 Topics Covered
- Creating dictionaries  
- Accessing keys & values  
- Updating items  
- Removing items  
- Dictionary methods (`get`, `items`, `keys`, `values`, `pop`, `update`, etc.)  
- Looping through dictionaries  
- Nested dictionaries  
- Practical examples  

---

## 🚀 Example Code

```python
sample = {"name": "Satyam", "age": 25}

# accessing
print(sample.get("name"))

# updating
sample.update({"city": "Toronto"})

# looping
for key, value in sample.items():
    print(key, value)
