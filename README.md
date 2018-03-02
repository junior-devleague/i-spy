# i-spy

I spy... a desk, an eraser, a class pet? Let's find some interesting objects in your classroom!

## Objective

Use **JavaScript Objects** to represent objects in your classroom.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of JavaScript and DOM.

## Concepts

JS | Description
-----|------------
JS | **J** ava **S** script used to create the function of web pages.
Object | Variables that can contain many values.

You already learned about variables. They look something like this:

``` JavaScript
var animal = "puppy";
```

Objects are variables that can store many values within them! Take a look at the general structure of an object which we've stored in a variable called puppy.

``` javascript

var puppy = {
  name: "Max",
  age: 3,
  breed: "beagle",
  hasOwner: true
}
```

Notice that objects have:
  * **name:value** pairs, or you can call them **properties** (name and value separated by a colon)
    * There are 4 name:value pairs/properties in our puppy object.
  * **comma** instead of semicolon after each line (except for the last line)
  * **ability to store many different types of values**
    * There are strings, integers, and booleans present!

How do we access these values from our object? Use a dot between the variable name and the property name!

``` JavaScript
console.log(puppy.name) //Prints "Max".

console.log(puppy.age)
//Prints "3".

console.log(puppy.breed)
//Prints "beagle"
//and so on and so forth!
```

Find out more at: https://www.w3schools.com/js/js_objects.asp

## Your Challenge

### Part 1

To complete Part I, fulfill the following requirements:

1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* JS file
* assets folder (from this folder)
3. Link all of your files correctly.

### Part II I Spy Objects!

To complete Part II, fulfill the following requirements:

1. In your JS file create an ```object``` in a variable called ```student1```. This object will have four properties:
  * name: String
  * age: Integer
  * haircolor: String
  * favoriteAnimal: String

Find a student to represent student1. Fill in their name, age, haircolor, and favoriteAnimal with the correct value types (String or Integer).

2. Create an ```object``` in a variable called ```student2```. This object will have four properties:
  * name: String
  * age: Integer
  * haircolor: String
  * favoriteAnimal: String

3. Create an ```object``` in a variable called ```student3```. This object will have four properties:
  * name: String
  * age: Integer
  * haircolor: String
  * favoriteAnimal: String

4. Create an ```object``` in a variable called ```technology```. Find an object that is techy in your classroom. This object will have two properties:
  * name: String
  * adjective: String

5. Create an ```object``` in a variable called ```storage```. Find an object that is used for storage in your classroom. This object will have two properties:
  * name: String
  * adjective: String

6. Create an ```object``` in a variable called ```usefulItem```. Find an object that is a useful item in your classroom. This object will have two properties:
  * name: String
  * adjective: String

7. Create an ```object``` in a variable called ```pet```. If you do not have a classroom pet, fill this object in with what you would want to have as a classroom pet. This object will have 3 properties:
  * name: String
  * type: String (rabbit, hamster...etc.)
  * adjective: String

## Stretch Goal

1. In your HTML file, do the following:
  * Create an ```audio``` element with an ```id``` of "sound". Make sure it has the correct ```src``` to the "pup1.mp3" sound file.
  * Create an ```img``` element with an ```id``` of "puppy". Make sure it has the correct ```src``` to the "puppy.jpg" image file.
2. In your JS file, do the following:
  * Create a variable called ```sound``` that will store the sound element. Hint: Use ```document.getElementById``` - https://www.w3schools.com/jsref/met_document_getelementbyid.asp
  * Create a variable called ```img``` that will store the puppy image element.
  * In your ```pet``` object, make another property called ```makeSound```. This will store a ```function``` that will play the sound! Resource: https://www.w3schools.com/js/js_objects.asp
  * Create an ```onclick``` function on your ```img``` element. When the image is clicked, play the pet sound using the pet object! Hint: How do we access properties from objects?
