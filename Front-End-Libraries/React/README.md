# Create a Simple JSX Element

The current code uses JSX to assign a div element to the constant JSX. Replace the div with an h1 element and add the text Hello JSX! inside it.



# Create a Complex JSX Element

Define a new constant JSX that renders a div which contains the following elements in order:

An h1, a p, and an unordered list that contains three li items. You can include any text you want within each element.



# Add Comments in JSX

The code editor has a JSX element similar to what you created in the last challenge. Add a comment somewhere within the provided div element, without modifying the existing h1 or p elements.



# Render HTML Elements to the DOM

The code editor has a simple JSX component. Use the ReactDOM.render() method to render this component to the page. You can pass defined JSX elements directly in as the first argument and use document.getElementById() to select the DOM node to render them to. There is a div with id='challenge-node' available for you to use. Make sure you don't change the JSX constant.



# Define an HTML Class in JSX

Apply a class of myDiv to the div provided in the JSX code.



# Learn About Self-Closing JSX Tags

Fix the errors in the code editor so that it is valid JSX and successfully transpiles. Make sure you don't change any of the content - you only need to close tags where they are needed.



# Create a Stateless Functional Component

The code editor has a function called MyComponent. Complete this function so it returns a single div element which contains some string of text.



# Create a React Component

MyComponent is defined in the code editor using class syntax. Finish writing the render method so it returns a div element that contains an h1 with the text Hello React!.



# Create a Component with Composition

In the code editor, there is a simple functional component called ChildComponent and a React component called ParentComponent. Compose the two together by rendering the ChildComponent within the ParentComponent. Make sure to close the ChildComponent tag with a forward slash.



# Use React to Render Nested Components

There are two functional components defined in the code editor, called TypesOfFruit and Fruits. Take the TypesOfFruit component and compose it, or nest it, within the Fruits component. Then take the Fruits component and nest it within the TypesOfFood component. The result should be a child component, nested within a parent component, which is nested within a parent component of its own!



# Compose React Components

Nest two components inside of Fruits — first NonCitrus, and then Citrus. Both of these components are provided for you in the background. Next, nest the Fruits class component into the TypesOfFood component, below the h1 header and above Vegetables. The result should be a series of nested components, which uses two different component types.



# Render a Class Component to the DOM

Both the Fruits and Vegetables components are defined for you behind the scenes. Render both components as children of the TypesOfFood component, then render TypesOfFood to the DOM. There is a div with id='challenge-node' available for you to use.



# Write a React Component from Scratch

Define a class MyComponent that extends React.Component. Its render method should return a div that contains an h1 tag with the text: My First React Component! in it. Use this text exactly, the case and punctuation matter. Make sure to call the constructor for your component, too.

Render this component to the DOM using ReactDOM.render(). There is a div with id='challenge-node' available for you to use.



# Pass Props to a Stateless Functional Component

There are Calendar and CurrentDate components in the code editor. When rendering CurrentDate from the Calendar component, pass in a property of date assigned to the current date from JavaScript's Date object. Then access this prop in the CurrentDate component, showing its value within the p tags. Note that for prop values to be evaluated as JavaScript, they must be enclosed in curly brackets, for instance date={Date()}



# Pass an Array as Props

There are List and ToDo components in the code editor. When rendering each List from the ToDo component, pass in a tasks property assigned to an array of to-do tasks, for example ["walk dog", "workout"]. Then access this tasks array in the List component, showing its value within the p element. Use join(", ") to display the props.tasks array in the p element as a comma separated list. Today's list should have at least 2 tasks and tomorrow's should have at least 3 tasks.



# Use Default Props

The code editor shows a ShoppingCart component. Define default props on this component which specify a prop items with a value of 0.



# Override Default Props

The ShoppingCart component now renders a child component Items. This Items component has a default prop quantity set to the integer 0. Override the default prop by passing in a value of 10 for quantity.

Note: Remember that the syntax to add a prop to a component looks similar to how you add HTML attributes. However, since the value for quantity is an integer, it won't go in quotes but it should be wrapped in curly braces. For example, {100}. This syntax tells JSX to interpret the value within the braces directly as JavaScript.



# Use PropTypes to Define the Props You Expect

Define propTypes for the Items component to require quantity as a prop and verify that it is of type number.



# Access Props Using this.props

Render an instance of the ReturnTempPassword component in the parent component ResetPassword. Here, give ReturnTempPassword a prop of tempPassword and assign it a value of a string that is at least 8 characters long. Within the child, ReturnTempPassword, access the tempPassword prop within the strong tags to make sure the user sees the temporary password.



# Review Using Props with Stateless Functional Components

The code editor has a CampSite component that renders a Camper component as a child. Define the Camper component and assign it default props of { name: 'CamperBot' }. Inside the Camper component, render any code that you want, but make sure to have one p element that includes only the name value that is passed in as a prop. Finally, define propTypes on the Camper component to require name to be provided as a prop and verify that it is of type string.



# Create a Stateful Component

There is a component in the code editor that is trying to render a name property from its state. However, there is no state defined. Initialize the component with state in the constructor and assign your name to a property of name.



# Render State in the User Interface

In the code editor, MyComponent is already stateful. Define an h1 tag in the component's render method which renders the value of name from the component's state.

Note: The h1 should only render the value from state and nothing else. In JSX, any code you write with curly braces { } will be treated as JavaScript. So to access the value from state just enclose the reference in curly braces.



# Render State in the User Interface Another Way

In the MyComponent render method, define a const called name and set it equal to the name value in the component's state. Because you can write JavaScript directly in this part of the code, you don't have to enclose this reference in curly braces.

Next, in the return statement, render this value in an h1 tag using the variable name. Remember, you need to use the JSX syntax (curly braces for JavaScript) in the return statement.



# Set State with this.setState

There is a button element in the code editor which has an onClick() handler. This handler is triggered when the button receives a click event in the browser, and runs the handleClick method defined on MyComponent. Within the handleClick method, update the component state using this.setState(). Set the name property in state to equal the string React Rocks!.

Click the button and watch the rendered state update. Don't worry if you don't fully understand how the click handler code works at this point. It's covered in upcoming challenges.



# 
