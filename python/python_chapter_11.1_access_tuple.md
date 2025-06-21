# 🔍 Accessing Tuple Items

Tuples in Python are **ordered**, so you can access items using **indexing** and **slicing**, just like lists. Remember, tuple items are **zero-indexed**, meaning the first item has index `0`.

> Example

>```python
>fruits = ("apple", "banana", "cherry")
>
>print(fruits[0])   
>print(fruits[2]) 
>```

**Output**

>```
>apple
>
>cherry
>```

## 🔁 Negative Indexing

Negative indexing allows you to access items from the **end** of the tuple.

> Example

>```python
>fruits = ("apple", "banana", "cherry")
>
>print(fruits[-1])   
>print(fruits[-2])   
>```

**Output**

>```
>cherry
>
>banana
>```

## ✂️ Slicing Tuples

You can access a **range of items** in a tuple using slicing: `tuple[start:end]`.

> Example

>```python
>numbers = (10, 20, 30, 40, 50)
>
>print(numbers[1:4])   
>print(numbers[:3])     
>print(numbers[2:])     
>```

**Output**

>```
>(20, 30, 40)
>
>(10, 20, 30)
>
>(30, 40, 50)
>```

## 🎥 YouTube

![youtube]()

<div style="display: flex; justify-content: space-between; margin-top: 30px;">
  <a
  href="python_chapter_11.0_python_tuple.md" style="text-decoration: none; font-weight: bold;">⬅️ Previous</a>
  <a 
  href="python_chapter_11.2_update_tuple.md" style="text-decoration: none; font-weight: bold;">Next ➡️</a>
</div>
