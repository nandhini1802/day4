// How to compare two JSON have the same properties without order?

var obj1 = {name: "Person1", age: 5};
var obj2 = {age: 5, name: "Person1"};

console.log(JSON.stringify(obj1) === JSON.stringify(obj2)); // false

// Two JSON have the same properties with same order
var obj3 = {name: "Person1", age: 5};
var obj4 = {name: "Person1", age: 5};

console.log(JSON.stringify(obj3) === JSON.stringify(obj4)); // true

// Two JSON have the same properties with same order but one property(name) having different values 
var obj5 = {name: "Person1", age: 5};
var obj6 = {name: "Person2", age: 5};

console.log(JSON.stringify(obj5) === JSON.stringify(obj6)); // false

// Two JSON have the same properties with same order but one property(age) having different values 
var obj7 = {name: "Person1", age: 5};
var obj8 = {name: "Person1", age: 10};

console.log(JSON.stringify(obj7) === JSON.stringify(obj8)); // false

// Two JSON have the same properties with same order but both properties having different values 
var obj9 = {name: "Person1", age: 5};
var obj10 = {name: "Person2", age: 10};

console.log(JSON.stringify(obj9) === JSON.stringify(obj10)); // false

// Two JSON have the same properties without order and also both properties having different values 
var obj9 = {name: "Person1", age: 5};
var obj10 = {age: 10, name: "Person2"};

console.log(JSON.stringify(obj9) === JSON.stringify(obj10)); // false