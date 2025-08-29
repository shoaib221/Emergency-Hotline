# B12-A5-Emergency-Hotline

What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
1. getElementById() method selects a single element with a specific id. getElementsByClassName() method slects an array of elements by a given class name. querySelector() method selects the first element with a given query parameter. querySelectorAll() method selects all the elements with a given query parameter. 

2. createElement() method is used firstly to create an elelment with specific tag name. Then appendChild() method is used to append the element into a specific parent node. 

3. An event is firstly occured in the innermost element and then it propagates through its parent elements gradually. This propagation is called event bubbling. 

4. During event bubbling an event can be listened by an upper parent node. This is called event delegation. It is usefull for appointing event listener to dynamic child nodes. 

5. preventDefault()  prevents the default functionality of an event handler. stopPropagation() method prevents a method from propagating to its parent. 
