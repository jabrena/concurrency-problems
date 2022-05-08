# concurrency-problems

A collection of problems about concurrency scenarios to learn about Java Memory Model

## Motivation

## JVM Concurrency Pilars

**Infrastructure:**

- Modern CPU Architectures
- JVM Architecture

**Concepts:**

- Java Memory Model, JMM
- Ordering
- Visibility
- Liveness
- Affinity

**Problems:**

- Synchronization
- Atomicity
- Shared State
- Deadlocks
- Data races
- Cache coherence

**Possible solutions:**

- Immutable Objects
- Locks
- Atomic Objects
- Volatile
- Concurrent collections
- Synchronized collections
- ThreadLocal

## Problems

### Problem 1: Counter

``` gherkin 
Feature: Develop a Class which manage a Simple Counter

Background: The class need to be Thread Safe

Scenario: Provide information about a Counter
    Given a class which manage a Counter
    When  call the method getCounter()
    Then  returns the counter value
    
Scenario: Increment the Counter
    Given a class which manage a Counter
    When  call the method increment()
    Then  increment the counter value    
```

### Problem 2: Fibonacci

``` gherkin 
Feature: Develop a Class in charge of Fibonacci

Background: The class need to be Thread Safe

Scenario: Consume Fibonacci numbers
    Given a class which generate Fibonacci Numbers
    When  call the method X
    Then  returns the number
```






