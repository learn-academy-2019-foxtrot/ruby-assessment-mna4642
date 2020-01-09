# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer:
They both have a function, loop, argument statement, blocks.
Javascript uses console.log whereas Ruby use puts. Ruby end the methods with "end" whereas JS end with return, but Ruby can use return, but must end the blocks.  
Ruby uses def while JS uses variable and const. 

  Researched answer:
  JavaScript can be used as front-end and back-end language using the same language whereas, Ruby is used as back-end programming language.JavaScript is more scalable than Ruby as it is 20 times faster than Ruby in some cases. JavaScript has no ability to monitor memory utilization whereas Ruby has the ability.





2. What is a hash?

  Your answer:
  hash is a similar concept of the relationship between two entities such as animals => 4 legs (animals with only 4 legs).

  Researched answer:
  A Hash is a collection of key-value pairs like this: "employee" = > "salary". It is similar to an Array, except that indexing is done via arbitrary keys of any object type, not an integer index.
The order in which you traverse a hash by either key or value may seem arbitrary and will generally not be in the insertion order. If you attempt to access a hash with a key that does not exist, the method will return nil.






3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer:
  Testing framework in ruby is a testing using to test your work enviornment in ruby.

  Researched answer:
test-unit (Test::Unit) is unit testing framework for Ruby, based on xUnit principles. It allows writing tests, checking results and automated testing in Ruby.





4. Name three possible relationships between objects?

  Your answer:
  Class
  Blocks
  Lambdas

  Researched answer:
Blocks, lambdas, Class




5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer:
  Variable in Ruby is defined in class. Other variable are not defined in class.

  Researched answer
  n object-oriented programming with classes, an instance variable is a variable defined in a class (i.e. a member variable), for which each instantiated object of the class has a separate copy, or instance. An instance variable is similar to a class variable.





6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) Collection- using hash#each, hash#fetch, hash#key?

2) Percent Literals Braces
() for string literals (%q, %Q).

[] for array literals (%w, %i, %W, %I) as it is aligned with the standard array literals.

{} for regexp literals (%r) since parentheses often appear inside regular expressions. That’s why a less common character with { is usually the best delimiter for %r literals.

() for all other literals (e.g. %s, %x)

3) Classes: Constructors:
Factory Methods and Disjunctive Assignment in Constructor


7. STRETCH: What are blocks, procs, and lambdas?

  Your answer:
  Blocks are like components break down into pieces. Start with “def” and end with “end” or “puts.”

Procs are probably something related to the block in term of saving the block to be used later in another coding event. 

Lambdas is used to for return method as it is pass on in the argument using procs

  Researched answer:
In Ruby, blocks are snippets of code that can be created to be executed later. Blocks are passed to methods that yield them within the "do" and "end" 
A “proc” is an instance of the Proc class, which holds a code block to be executed, and can be stored in a variable. To create a proc, you call Proc.new and pass it a block.
Lambdas are essentially procs with some distinguishing factors. They are more like “regular” methods in two ways: they enforce the number of arguments passed when they’re called and they use “normal” return