# Problem Description:
(Geometric Objects) 
### Design a class named Circle that extends GeometricObject. The class contains: 

*	A double data field named radius with default values 1.0.
*	A no-arg constructor that creates a default Circle.
*	A constructor that creates a Circle with specified radius.
*	The accessor method for the radius.
*	A method named getArea() that returns the area of the circle.
		
	```bash
		area = Math.PI * radius * radius;
	```
*	A method named getPerimeter() that returns the perimeter of this Circle (2*Math.PI*radius). 
*	A method named toString() that returns a string description for the Circle. The toString() method is implemented as follows:
		
	```bash
		return "Circle: radius = " + radius;
	```
		
### Design a class named Rectangle that extends GeometricObject. The class contains: 

*	Two double data fields named side1 and side2 with default values 1.0 to denote the two sides of a Rectangle.
*	A no-arg constructor that creates a default Rectangle.
*	A constructor that creates a R with specified side1 and side2.
*	The accessor methods for all two data fields.
*	A method named getArea() that returns the area of the Rectangle.
		
	```bash
		area = side1 * side2;
	```
*	A method named getPerimeter() that returns the perimeter of this Rectangle (2*side1 + 2*side2). 
*	A method named toString() that returns a string description for the Rectangle. The toString() method is implemented as follows:
		
	```bash
		return "Rectangle: side1 = " + side1 + " side2 = " + side2;
	```
		
### Design a class named Triangle that extends GeometricObject. The class contains: 

*	Three double data fields named side1, side2 and side3 with default values 1.0 to denote the three sides of a triangle.
*	A no-arg constructor that creates a default triangle.
*	A constructor that creates a triangle with specified side1, side2 and side3.
*	The accessor methods for all three data fields.
*	A method named getArea() that returns the area of the triangle.
		
	```bash
		s = (side1 + side2 + side3)/2;
		area = Math.sqrt(s*(s-side1)*(s-side2)*(s-side3));
	```
*	A method named getPerimeter() that returns the perimeter of this triangle. 
*	A method named toString() that returns a string description for the triangle. The toString() method is implemented as follows:
		
	```bash
		return "Triangle: side1 = " + side1 + " side2 = " + side2 + " side3 = " + side3;
	```
		
## Tasks
* Design: Draw the UML class diagram that involves the classes Triangle, Circle, Rectangle and GeometricObject.
* Code: Implement the classes
* Write a test program that creates an array of GeometricObjects and has members of Circle, Rectangle and Triangle objects.
 The test program should go through the array and print the class of the object and the properties of the object such as the sides, area, perimeter, color, dateCreated, and whether it is filled or not. 
* Submit the files using git

