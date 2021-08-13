# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    The Context API was created to solve a specific problem in react, sharing state down a component tree. Similar to the solution that Redux and React-Redux libraries solve, this solution prevents prop drilling

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    This makes it easy to create universal apps, as the state from your server can be serialized and hydrated into the client with no extra coding effort. A single state tree also makes it easier to debug or inspect an application; it also enables you to persist your app's state in development, for a faster development cycle

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. ... Redux Thunk allows us to dispatch those actions asynchronously and resolve each promise that gets returned.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    Context API, bit easy, without the props drilling, kindly new but i think it will get there 