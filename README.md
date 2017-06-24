# Assignment-13.4

Compare Relay and React with MVC or MVVM model


Relay, is highly opinionated framework, many call it as a magic, when we consider how

it works. But under the hood, Relay is built out of the Flux model, with a single Store

(Unlike multiple Store model proposed by Flux). So before we start, let’s learn about

Flux and how Flux pattern is better than MVC.

• Flux is an application architecture or pattern to build a scalable data driven web app.

Flux is often confused with a UI framework, which it is not.


* For MVVM development model, the developers will be defined as three different classes, to achieve the performance, data, control separation. More from the technical point of view of the UI to split, to achieve loose coupling. 

* For React, it is entirely a new idea, the developer from the functional point of view, the UI is divided into different components, each component is individually packaged.

MVVM is a great pattern which allows for a clean separation between views and logic, it also lends itself well to unit testing, but is it the only way? If you didn’t already know there’s some new kids on the block, Unidirectional User Interface Architectures which is basically applying the CRQS/Event Sourcing pattern on the client side. The idea of these patterns is to have a single DataStore which is the source of truth and data is updated via events, all Views read from the single source of Data and can only update via events/actions. 
