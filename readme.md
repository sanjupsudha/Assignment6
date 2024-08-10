 ## 1. Write short notes on Array methods with code example
### -> push()
### -> pop()
### -> shift()
### -> unshift()
### -> includes()
### -> toString()
### -> reverse()
### -> join()
### -> concat()
### -> flat()
### -> slice()
### -> splice()
### Ans • push(): push() is used to add an element to the end of an array.
### let arr=[1,2,3,4]
### arr.push("six")
### console.log(arr)
### • pop(): pop() is used to remove the last element from an array.
### let arr=[1,2,3,4]
### arr.pop(3)
### console.log(arr)
### • shift(): shift() removes the first element from an array and returns it.
### let arr=[1,2,3,4]
### arr.shift()
### console.log(arr)
### • unshift(): unshift() adds one or more elements to the beginning of an array and returns the new length.
### let arr=[1,2,3,4]
### arr.unshift("zero")
### console.log(arr)
### • includes(): checks if a specific element or substring is present in an array or a string, respectively. It returns a boolean value.
### let arr=[1,2,3,4]
### arr.includes(5)
### console.log(arr)
### • toString(): toString() method is used to turn numbers, booleans, arrays, and objects into strings.
### let arr=[1,2,3,4]
### console.log(arr.toString())
### • reverse(): The reverse() method reverses the order of the elements in an array. The reverse() method overwrites the original array.
### let arr=[1,2,3,4]
### console.log(arr.reverse())
### • join(): The join() method takes all items in an iterable and joins them into one string.
### let arr=[1,2,3,4,5]
### console.log(arr.join(" "))
### • concat(): The concat() method concatenates (joins) two or more arrays. The concat() method returns a new array, containing the joined arrays.
### let arr=[1,2,3,4]
### let newarr=[5,6,7,8]
### console.log(arr.concat(newarr))
### • flat(): creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.
### let arr=[[1,2],[3,4],[5,6]]
### console.log(arr.flat())
### • slice(): The slice() method returns selected elements in an array, as a new array. The slice() method selects from a given start, up to a (not inclusive) given end.
### let arr=[1,2,3,4,5]
### console.log(arr.slice(0,2))
### • splice(): The splice() method of Array instances changes the contents of an array by removing or replacing existing elements and/or adding new elements
### let string=["may","june","july"]
### string.splice(1,2,"december")
### console.log(string)
## 2. ![screenshort2](./screenshort%202.png)
## 3. Write a JavaScript function to check whether an input is an array.
### Ans.let arr=['output','input','result']
 ### console.log(arr.isArray(arr))
## 4. Write a JavaScript function that takes an array as an argument and returns the first element of the array.
### Ans.let arr=[1,2,3,4]
### let firstElement=(Array)=>{
  ###  return Array.shift()
### }
### let result=firstElement(arr)
### console.log(result);
## 5. Write a JavaScript function that takes an array as an argument and returns the last element of the array.
### let arr=[1,2,3,4,5]
### let lastElement=(item)=>{
 ### return item.pop()  
### }
### let result=lastElement(arr)
### cosole.log(result)
## 6. Write a simple JavaScript function to join all elements of the following array into a string.
### Sample array : myColor = ["Red", "Green", "White", "Black"];
### Ans.let myColor = ["Red", "Green", "White", "Black"];
 ### console.log(myColor.join(" "))
## 7. Write a JavaScript program that accepts a number as input and inserts dashes (-) between each. For example, if you accept 025468 the output should be 0-2-5-4-6-8
### Ans.let num =23520
### let output = num.toString().split ("")
### let join=output.join("-")
### console.log(join)
## 8. Write a JavaScript function that checks if the given number is even or odd then returns a Boolean value (use: arrow function, return keyword, ternary operator)
### Ans.let num = 56
### let isEven=(number) =>{
### let result= number % 2=== 0 ? console.log(true): console.log(false);
### return result
### }
### isEven(num)
## 9. Create an array of guestlist. Write a javascript function that takes the user’s name as an argument and checks if it is there in the guestlist. If yes, return the string “Welcome” else, return “Sorry, good luck next time”.
### Ans.let checkGuestList = (name) =>{
  ###  let guestList =["sajla","bijila","subin","sanju","anusha"]
   ### return guestList.includes(name)? console.log("welcome"):console.log("Sorry, good luck next time");
  ### }
 ### checkGuestList("anusha")
## 10. Write a javascript function that reverses a given number example: 123456789 => 987654321 (split(), reverse (), join())
### Ans.let names=["neenu","anagha","vidhun"]
### console.log(names.reverse())
##  11. Write a JavaScript function that accepts a string as a parameter and converts the first letter into upper case.
### Example: “Javascript” => “Javascript”
### Ans.const string = "name";
### const editString = string[0].toUpperCase() + string.slice(1);
### console.log(string)
### console.log(editString);