# React Tic-Tac-Toe Tutorial

Short intro [tutorial](https://react.dev/learn/tutorial-tic-tac-toe) from React's website.

App can be run by:
1. `npm install`
2. `npm start`

Few key learnings from this first React experience:

- React component names must always start with a capital letter as HTML tags must be lowercase
- Curly braces let you “escape back” into JavaScript from JSX so that you can embed some variable from your code
- State is private to the component that defines it. You can pass functions between components which can modify state in other components
- When altering the state of a component you re-render that component and all of its children
- Conventional to use onSomething names for props which represent events and handleSomething for the function definitions which handle those events