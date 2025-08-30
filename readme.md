1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

ans:
getElementById → Finds one element by its id.

getElementsByClassName → Finds many elements with the same class. Returns a collection.

querySelector → Finds the first element that matches a CSS selector.

querySelectorAll → Finds all elements that match the CSS selector. Returns a list.

2. How do you **create and insert a new element into the DOM**?

ans:
Create element → document.createElement

Add text/content → element.textContent = "Hello"

Insert into DOM → parent.appendChild

3. What is **Event Bubbling** and how does it work?

ans:
When you click a child element, the event doesn’t stop there. It bubbles up first button then parent div then body then html document.
Means event moves upward through parents.

4. What is **Event Delegation** in JavaScript? Why is it useful?

ans:
Instead of adding event listeners to many child elements, you add one listener to their parent.
Then check which child was clicked using
"event.target".

Useful because:
Less code.
Works for dynamically added elements.
Saves memory and performance.

5. What is the difference between **preventDefault() and stopPropagation()** methods?

ans:
preventDefault() → stop the browser’s normal behavior.
stopPropagation() → stop event from moving to parent elements.