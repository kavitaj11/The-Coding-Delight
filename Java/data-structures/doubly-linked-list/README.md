# Doubly Linked List Implementation

This is an implementation of the doubly linked list data structure for my upcoming blog post on my <a href="https://www.thecodingdelight.com">blog</a>.

# API Documentation

## `void insert(T data)`

Insert data to the end of the list.

 * **Parameters:** `data` — the data to add.

     <p>

## `void insertAfter(T data, int index)`

Insert data after the node at a specific index.

 * **Parameters:**
   * `data` — the data to add.
   * `index` — the index of node after which we will add data.

     <p>

## `void remove(T data)`

Search from the start of the list and find data to remove.

 * **Parameters:** `data` — the data to remove.

     <p>

## `void removeFromFront()`

Remove first item from the list. In another word, remove the head node.

## `void removeFromBack()`

Remove last item from the list. In another word, remove the tail node.

## `void removeAt(int index) throws IndexOutOfBoundsException`

Remove the item at the nth index of the list.

 * **Parameters:** `index` — the index of the item to remove
 * **Exceptions:** `IndexOutOfBoundsException` — <p>

## `void print()`

Print items inside of the list.

## `int size()`

Get the size of the list.
