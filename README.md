# ReduxStore

# 22 State Homework: Redux Store



In this unit, we learned how to manage global state using React’s Context API. The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application, good future job practice!

We were challenged to refactor the e-commerce platform from [Activity 26](../01-Activities/26-Stu_Actions-Reducers/Unsolved) so that it uses [Redux]
## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```
![Screenshot (415)](https://user-images.githubusercontent.com/83887301/141009587-3da99c55-a05c-429f-8df0-334875c0570e.png)
![Screenshot (412)](https://user-images.githubusercontent.com/83887301/141009590-8d98dc5f-9ca9-4cde-8be9-22e277942bd7.png)
![Screenshot (413)](https://user-images.githubusercontent.com/83887301/141009591-09f0d8e4-6fe2-4554-863b-2c5e9e1dfb1d.png)
![Screenshot (414)](https://user-images.githubusercontent.com/83887301/141009592-01ae1b6a-b237-4be6-94c8-e7777c450c13.png)
