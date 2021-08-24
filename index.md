10 Javascript best practices tips

1. Minimize the use of Global Variables : it is better to use local variables and proper closures
2. Always Declare Local Variables : all variables within a function should be self contained. You declare local variables with let, var
3. Put your declarations on top : ie. declare all the variables within a function as your first line of code within a section, then define them later
4. Initialize the variables : Good practice in conjunction with declaring them on top. Gives you an idea of what you will use them for later
5. Declare OBJECTS and ARRAYS with const: prevents any accidental change of type later on.
6. Use === : helps avoid data coercion
7. Make lots of comments : comments help you break up cleanly, as well as quickly find sections and areas of code that
8. Arrow Functions are a Great New Tool : They exist within their parent scope and will act within the definitions of the parent to simplify functions that don't use apply, bind, call, or super
9. Write shorter loops with array methods : shorten long loops by placing data within arrays and using arrow functions
10. Shorten conditionals with falsy values : == means that two things share the same value, === means they are identical. There are many values that are equivalent to boolean false and will shorten your long conditional

Sources:

1. https://www.w3schools.com/js/js_best_practices.asp
2. https://www.educative.io/blog/javascript-tips-simplify-code
3. https://deepsource.io/blog/javascript-code-quality-best-practices/
