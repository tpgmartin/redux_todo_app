#Redux Todo App

##Notes

* In Redux, dispatch events are triggered separately from action creator
* React lets you describe UI as a function of state
* A container is just a React component that uses `store.subscribe` to read a 
part of the Redux state tree and supply props to a presentational component it renders
* Container components can both read state, via `mapStateToProps`, and dispatch actions, `mapDispatchToProps`
* To create a new container component, call `connect` to wire together the two methods above