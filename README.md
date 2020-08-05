# Bey-Slay

You are given an api.js file that exports an array of objects that look like this:
  > `{ "id": 1, "name": "All Day Slay", "img": "https://media.giphy.com/media/3o6gb7cN7bwDxAbnS8/giphy.gif", "favorite": false }`

# Deliverables:

- Render a list of all Beyonce images
- When a User clicks on a Beyonce image in `BeyContainer` it should change the `favorite` key of that object to `true`, which should then add that Beyonce to the FavoritesContainer, or `false`, which should then remove it from the FavoritesContainer

# What are we practicing?

- using both functional and class components
- deciding which component should make our api request
- deciding which component(s) should have state
- changing the state of a parent component from its child
- passing a callback function as a prop to be used by a child component
- manipulating objects inside of arrays in state
- reusing a component
- lifting state

![beyonce gif](bey-slay.gif)
