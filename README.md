Simple MVC
================================

An MVC 101 source to help you get started developing Javascript Web Applications. 

What is MVC?
--------------------------------

MVC is a design pattern that breaks an application into three parts:

1. The data (model).
2. The presentation layer (view).
3. The user interaction Layer (controller). 

Example

1. The user adds an item to a shopping basket.
2. The controller's event handlers trigger.
3. The controller creates a new item in the model.
4. The controller updates the view.

There are many frameworks that implement an MV* type approach to application architecture, however it is not necessary to use one. The key is to divide up responsibility of each of the components keeping them decoupled.


The Model
--------------------------------

The model is where all the applications data is stored. These are stored in the form of JavaScript objects. 

<pre>
{
	airline: 'Oceanic',
	number: '815',
	departure: {
		IATA: 'SYD',
		time: '2004-09-22 14:55',
		city: 'Sydney'
	},
	arrival: {
		IATA: 'LAX',
		time: '2004-09-23 10:42',
		city: Los Angeles
	}
}


</pre>