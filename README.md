Download Link: https://assignmentchef.com/product/solved-circular-linked-list
<br>
5/5 - (1 vote)

1. A circular list is a linked list in which the last link points back to the first link. There are many ways to design a circular list. Sometimes there is a pointer to the “start” of the list. However, this makes the list less like a real circle and more like an ordinary list that has its end attached to its beginning. Define a class for a singly linked circular list that has no end and no beginning The only access to the list is a single reference, current, that can point to any link on the list. This reference can move around the list as needed. Your list should handle insertion, searching and deletion.



You may find it convenient if these operations take place one link downstream of the link pointed to by current. (Because the list is a singly linked list, you can’t get the upstream link without going all the way around the circle.) You should also be able to display the list. A step() method that moves current along to the next link might come in handy too. Write a driver class to test the circular list.Hint:a) The data members of class circular linked list should include the reference current and a variable to track the size of links in the circular list.

b) The methods needed to define in the class circular include:insert: insert after current link delete:

delete one beyond current .find: find link with given key edeleteKey: delete link with given keydisplayList: display the list (all the links in the list)step: move current to the next linkpeek: return the data stored in current .isEmpty: check whether the list is empty

2. Implement a stack class based on the circular list created in the previous question. Write a driver class to test the circular list based stack.