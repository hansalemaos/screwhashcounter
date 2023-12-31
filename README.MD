# provides a convenient and efficient way to count the occurrences of items (hashable and unhashable)

## pip install screwhashcounter

#### Tested against Windows 10 / Python 3.10 / Anaconda 

	
```python

Count the occurrences of items in a list, tuple and return a list of tuples with the item and its count.

Args:
	arg (list|tuple): The list|tuple containing items to be counted.

Returns:
	list[tuple]: A list of tuples where each tuple contains an item and its count.

Example:
	from screwhashcounter import countitems
	counted_items = countitems(
		["mississippi", [1, 2], [1, 2], {34, 4, 3}, {1: 2}, {1: 2}, None, 3]
	)
	print(counted_items)
	# Output: [('mississippi', 1), ([1, 2], 2), ({34, 3, 4}, 1), ({1: 2}, 2), (None, 1), (3, 1)]
```