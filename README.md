### This is my JAVASCRIPT AND REACT TUTORIAL WEBSITE. FOR EXPLANING ALL THE CONCEPTS OF JAVASCRIPT IN SIMPLE WORDS.

Clone the project and run it to start exploring! Enjoy straightforward tutorials accompanied by practical programming code. I crafted this while advancing through Meta's <b>Advanced React</b> course on Coursera.

## What is Reactjs?
Reactjs is an open-source, component based frontend javascript library for the view layer of the application. It is supported by Meta.

## What is Virtual DOM?
Reactjs utilizes a virtual DOM. The virtual DOM (Document Object Model) is a concept used by React to optimize the performance and efficiency of web applications.
- When a React component renders for the first time, React creates a virtual DOM tree based on the component's structure.
- When the state or props of a component change, React re-renders the component, creating a new virtual DOM tree.
- React then compares this new virtual DOM tree with the previous one using a process called "diffing". This process determines what has changed.
- Only the parts of the real DOM that have actually changed are updated, minimizing the number of manipulations needed and improving performance.

## What is Javascript map function and How does it work?
Javascript map method is used to transform a list, and list is a simple collection of elements (represents an array in javascript). Most common type of an element has in the array is Object. While fetching data from third party like this, you are generally provided with more data than you need. Map method ignores everything you don't want to display on the screen. Map method always returns a new array. In map function, one would return any datatype when you are working with lists in JSX. PLease refer to <a href="./mapFunction">mapFunctions</a><br/>

<b>Things to know about map function in Javascript</b>
- map() creates a new array from calling a function for every array element.
- map() does not execute the function for empty elements.
- map() does not change the original array.




