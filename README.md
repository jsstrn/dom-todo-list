# DOM Manipulation Lab: Todo List

## Tasks

### Displaying To-Do items in the list

- For each todo in the tasks array, append it to the `<ul id='todo-list'></ul>`
  element

- Create a css class (e.g. `.done`) that, when applied on an element, adds the
  `text-decoration: line-through` property

- Add a click listener to the `<li></li>` elements that adds the css class that
  you created in the previous step to the element that was clicked

- Update the callback function so that clicking on the list element toggles
  (i.e. add/remove) the `.done` css class (hint: take a look at the
  documentation for `.classList.toggle()`)

### Adding more To-Do items

- Add a `<input>` HTML element and a `<button>Add Todo</button>` HTML element.

- Add a 'click' event listener to the button that adds the value of the
  `<input>` element as a new todo in the `ul#todo-list` (follow the 3 steps for
  creating and appending a new DOM element - (i) `createElement`, (ii) change
  any attributes if necessary, (iii) use `appendChild` to append it to the
  appropriate HTML element)

- Add css styling and make this a nice todo list that you can show off!

- Bonus: Allow user to create a todo when they press the <kbd>Enter</kbd> key
