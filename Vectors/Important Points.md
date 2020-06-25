### Important concepts of vectors
- Vectors are **sequential containers** which behave like dynamic arrays,i.e, they store elements in contigous memory locations and can modify their size according to need.
- Supports **random access**. Operation on last element takes O(1) time whereas on other positions it takes O(N) time because insertion is done from end in vectors.
- Traversal is done using iterators. Iterators are objects that point to elements present inside containers.
- Some basic operations are
  - **push_back(arg):** Inserts element at the end of vector
  - **pop_back():** Removes element from end. It doesn't permanently delete the element but reduces the size of vector by 1 unit. The element still persists in vector's memory.
  - **vector_name.erase(iterator/start_iterator,end_iterator):** Completely deletes an element from vector's memory.
  - **vector_name.clear():** Completely deletes all the elements from a vector.
### Disadvantages of Arrays:
  1. Cannot modify the size of the array once initialized.
  2. Cannot delete elements from array.
  3. Array cannot store elements of different data types.