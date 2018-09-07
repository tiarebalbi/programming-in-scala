
# Chapter 1 - A Scalable Language

> The name Scala stands for "scalable language." The language is so named because it was designed to grow with the demands of its users. You can apply Scala to a wide range of programming tasks, from writing small scripts to building large systems.

----
* **Source Code:** [../src/main/scala/chapter01](src/main/scala/chapter01) 
* **Notes:**
 
    * Scala works with Java Threads but Scala introduced a new API to abstract concurrency, 
    Akka, an additional Scala library that implements an actor model similar to Erlang's.
    * Two actions of an Actor:
        * send message using the operator (!)
        * receive messages
