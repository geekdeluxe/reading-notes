# JavaScript Object Basics 

-An object is a really important building block...objects are containers for properties. According to MDN web docs, an object is a collection of related data and/or functionality. Objects can also have methods.

-The advantage to creating object literals is efficiency.

-Objects are easier to work with than arrays, according to MDN web docs. You'd use an array when you want to identify individual items by name. 

-You'd want to use a bracket notation to access an onject's property instead of a dot notation when using an array and also as another way to access object properties. Like this, for example: 

    animal["age"];
    animal["name"]["first"];
                                                        

-In the Code Fellows sample below, the term "this" is used as a "keyword which refers to the current object the code is being written inside," according to MDN web docs. MDN web docs goes on to say: the advantage of using "this" is that it allows you to used the same method definition for every object you create. Pretty neat.

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

# Introduction to the DOM

-The DOM is the document object model.

- The DOM and JavaScript are related in that the DOM allows web pages to be modified with JavaScript.

# Things I Want to Know More About 

-Nodes in JS and what nodes are in other aspects of tech
-Method chaining
-Linked lists
-React
-Rust (everyone's talking about it and says it's awesome!)
-Practice creating an HTML element in JS 
-Kubernetes (what's the fuss about? What is it? How does it work? Which  
 companies use it? Should I learn it?)
-Learn about the early days of programming and how things have changed.
