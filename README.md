# reactive-systems-notes
My own notes from the reative systems course

**Reactive:** *readily responsibe to a stimulus.*

* Event driven
* Scalable
* Resilient
* Responsive

#### Event driven

Events can be driven asynchronously, without blocking.

#### Scalable

Requirements for high scalability:

* Minimmize shared mutable state.
* Location transparency: Location doesn't matter.

#### Resilient
It can recover quickly from a failure. It needs to be part of the design of the system.

 * Loose coupling
 * Strong encapsulation
 * Pervasive supervisor hierarchies

 #### Responsive

 It provides rich, real-time interaction even under load or errors.

 ## About Events

 Handling events if often done using callbacks. But this approach has some problems:

 * Needs shared mutable states.
 * Hard to construct higher abstractions
 * Callback hell

 