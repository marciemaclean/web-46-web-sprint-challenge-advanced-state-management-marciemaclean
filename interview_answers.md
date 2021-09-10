# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
It makes it so you can do prop drilling way easier. Can also replace redux if you want to.
2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application? Actions pass information into the store, reducers change state, and the store holds state. Its called the single source of truth because it's where everything else gets state from.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
It's a middleware. Thunk allows you to wtire action creators that give back functions instead of actions.
4. What is your favorite state management system you've learned and this sprint? Please explain why!
I'm not sure honestly. It's all pretty complex so I think I need to work with them more before I can pick a definite favorite.