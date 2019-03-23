1. What are PropTypes used for? Please describe why it’s important to type check our data in Javascript.

	PropTypes are used for type checking our data as it get’s passed from one component to another. By doing this type checking we can be sure that we are passing and receiving the correct  type of data.

2. Describe a life-cycle event in React?

	A React component lifecycle consists of three phases which are Mounting, Updating, and Unmounting. An example event would be componentDidMount which is used to setup the initial state for the component and any asynchronous actions to be performed. CDM gets called as soon as the render method is called the first time.

3. Explain the details of a Higher Order Component?

	A HOC is a function the receives a component as an argument and returns a new component. Using this pattern allows us the ability to reuse logic or functionality between components.

4. What are three different ways to style components in React? Explain some of the benefits of each.

	You can import a stylesheet for your components and use CSS class names like you’re used to. You may use inline styles which have the highest specificity after !important. Or you can use styled-components which allows for reuse across your project. Styled-components also allow us to pass in props which gives us the ability to have variations of a component that basically have the same styling with some changes. This way we can define the component once and then use props to choose a different version of that component. 
