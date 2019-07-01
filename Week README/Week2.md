## Week 2

By the end of the week I should be able to use these things or explain why not to use them:

- Use all of week 1's skills (don't underestimate the importance of this)
- Break one class into two classes that work together, while maintaining test coverage
- Unit test classes in isolation using mocking
- Explain some basic OO principles and tie them to high level concerns (e.g. ease of change) - why would you choose these principles :
    -SRP
    -SOLID
    -Encapsulation
- Review another person's code and give them meaningful feedback

OO Patters :
- Polymorphism
- Delegation
- Dependency injection
- Inheritance 

## Monday


### Code Review :

First thing to read is README

- It works? -> Fulfil user needs - For computers:
    - test :
        - What do they do?
        - Are they passing? / Coverage
        - Use IRB or feature test
-  It's readable - For Humans ( Can everyone read it? Is it simple to understand?)
- Good naming
- Dry :
    - Less code to read
    - Easier to change
- SRP -> Does one thing

### What I have learned from Code Review:

- Learned about README
- Common bugs/ gaps
- Feedback is important:
      - Gives evidence of progress
      - team player
      - weaknesses to opportunities (helps you improve )
- At work you will rely a lot on feedback to develop
- It is hard to give feedback if you don't know if it's right or wrong

###  There are many solutions to one problem:
    - Options to do things differently
    - Learn other styles to have more options to solve your problems
    - There are no best solutions

### How to choose best style?
    - Consider your team
    - What is typical style of the team
    - Consider the rest of the code
    - Be consistent
    - use your experience ( be careful around this one! You might have bad habits and stop yourself from developing )

### Fix the Weather :
Options for technique :
MOCKING :
  - Doubling
  - Spies
  - Stubbing

Allowig_subject - bad practice


Importance of feature tests -> Checks if the whole system works well together

Fixing randomness :
1. Allowing things
2. Seeding the weather number generator
