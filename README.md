# KReact
KReact.createClass method is used to create component. In order to perform certain actions when a component is created or rendered or destroyed we are following some structure.
	constructor - triggers when component instance is created. Default values are added in this place. For a structure, we are adding all variables to one variable 'state'.
	componentWillMount - triggers after creating the instance and before rendering
	render - this will render elements in UI
	componentDidMount = triggers after rendered

KReact.createElement method is used to create an instance of passed in component.
instance.setState is used is rerender the page if items are updated.

	
	