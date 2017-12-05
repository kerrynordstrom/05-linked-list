 ##  Documentation
This app creates several linked lists via a constructor function and tests addition, deletion, and find functionality to ensure that correct information is passed through the constructor.

## Linked List Class

The linked list Class uses syntactic sugar to declare a function called LinkedList which establishes properties for this.value and this.next.

## Append function

My append function throws a type error should the new node not be an instance of a linked list, then checks to see if there is a next node, for which it determines there is no list and it makes the current node the only one.  Lastly, it will append to the next node if there is a next and return the resulting linked list.

## Find function

My find function first looks to see if this.next is null AND this.value does not equal the value passed to the function, then it will `return null`.  Or else, it will keep moving recursively to find the value on following results until it iterates through the entire linked list where it will `return this`.

## Remove function

My remove function first looks to see if this.next is nonexistent, which would imply that there is only one node, which will `return this`.  If it finds that `this.next === node`, it will make `this.next` into `this.next.next`, effectively removing the connection between those two nodes.  It will continue to move through the linked list until it finds that node.

## ##