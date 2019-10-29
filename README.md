1. This is the readme file which will go along with the makers academy Boris Bikes paring exercise covering TDD. making a change

2. Working with user stories

As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike is working

 Write down all the nouns in the User Stories
 Write down all the verbs in the User Stories
 Draw a table like the one above
 Organise the nouns and verbs into Objects and Messages within the table
 Draw a diagram that shows how your Objects will use Messages to communicate with one another

nouns  - person, bike, docking station, good bike
verbs - use, release, working

Objects           Messages
person            
bike              use
docking station   release
good bike         working

3. From a Domain Model to a Feature Test

4. 4.1 Write down the type of error
   NameError: uninitialized constant DockingStation

   4.2 Write down the file path where the error happened
   from (irb):1
   from /Users/student/.rvm/rubies/ruby-2.2.3/bin/irb:11:in `<main>'

   4.3 Write down the line number of the error
     from (irb):1

   4.4 Use the Ruby Documentation to find out what the error means
     This error occurs when the given name is invalid or undefined.

   4.5 Suggest one way of solving the error.
     Define the object first.
