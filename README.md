# Design patterns with Python

## Design Patterns
Well known solutions to recurring problem

## Why use design patterns
- No need to reinvent the wheels
- Helps to use the best practise

## Types of design patterns
- Creational Patterns
  - Used to create objects in a systematic way
  - Uses polymorphism
- Structural Patterns
  - Establishes useful relationships between software components in certain configurations
  - Uses inheritance
- Behavioral Patterns
  - Best practice of object interactions
  - Defining the protocol
  - uses methods and their signatures


## Understanding the pattern context
The pattern context consists of the following:
- Participants
  - Classes involved to form a design pattern
  - roles that the classes and objects are involved

- Quality Attributes that are needed to be addressed
  - Nonfunctional requirements
    - Usability, modifiability, reliability, perfromance, etc.
  - Effect on the entire software can only be adderssed by architectural solutions

- Forces
  - Various factors or trade-offs to consider
    - Manifested in quality attributes
    - Failure to consider these forces could cause unintended consequences
- Consequences
  - Side Effects
    - Better security but worse performance

The ultimate responsibility falls on the decision makers who will have to decide which design pattern to choose despite the consequences.


## Pattern language
- Consists of:
  - Name
    - Should capture the gist of the pattern
    - Becomes part of the vocabulary during the design process
    - Needs to be:
      - Meaningful
      - Memorable
  - Context
    - Provides a scenario on when the pattern may be used
    - Provides more insights on
      - when to use it and when not to
  - Problem
    - Describes a design challenge that the pattern is addressing
  - Solution
    - Specifies a pattern itself in terms of
      - Structure: relationships among elements
      - Behavior: interactions
  - Related patterns
    - List of other patterns
      - Used together with the pattern being described
      - Similar but different


## Creational Patterns

### Factory Pattern
- Encapluates the object creation
- Specializes in creating other objects