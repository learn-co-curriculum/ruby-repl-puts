# Let's test some Repls!!!!!

TESTING

Below are some puts and non-puts repls. They should all work. Check 'em out!

%%%

### Ruby Repl Puts

Write a method that puts "ruby" 3 times.

~~~ruby

def puts_ruby_three_times
  # code your solution here
end

# do not remove the line below
puts_ruby_three_times

~~~solution

def puts_ruby_three_times
  3.times do
    puts "ruby"
  end
end

puts_ruby_three_times

~~~validation

assert_output(response, "ruby\nruby\nruby\n")

~~~

%%%

Moving right along...

%%%

### Ruby Repl Puts pt II

Write one line of code that puts "repls are teh best"

~~~ruby

# code solution here

~~~solution

puts "repls are teh best"

~~~validation

assert_output(response, "repls are teh best\n")

~~~

%%%

%%%

### Ruby Repl - Regular (no puts)

Write a method that reverses a string, and call it, passing "12345" as an argument.

~~~ruby

# Code your solution here

~~~solution

def reverse(string)
  string.reverse
end

reverse("12345")

~~~validation

assert_equal(response, "54321")

~~~

%%%

One more repl..

%%%

### Javascript Repl

Directions: Write an array containing three strings, each saying "taylors gonna tay".

~~~javascript

// Code your solution here

~~~solution

['taylors gonna tay', 'taylors gonna tay', 'taylors gonna tay']

~~~validation

assert.equal(response.length, 3);
expect(response).to.be.a("array");

~~~

%%%

testing some stuff