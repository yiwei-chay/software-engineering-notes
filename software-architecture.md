# Software Architecture Patterns - Microservices

## Evolution of software architecture patterns (Comparison of patterns)
Software architecture patterns have evolved from monolithic to multitier and now to microservice-based architecture. 

Monolithic application is a straight-forwarded way of building a simple application is by building a single piece of code, encapsulating all the data, business logic and user interfaces. However, the limits of this architecture arised when more complex systems are being developed. This is because everything in a system dependent on each other and thus makes testing, development, deployment and debugging extra difficult. 

The microservice architecture is a software development methodology which aids the design, development, and maintenance of large-scale applications. Although it is composed of several independent services, the microservice applications still act as a standalone appliccation and end-users would have the same experience as monolithic applications. 

![image](https://github.com/yiwei-chay/software-engineering-notes/assets/146081571/84ff3f5a-3006-4457-bd59-6796d8ba0dc1)


## Characteristics of microservice architecture and design
1. Service APIs <br/>
Component-based architectures aim to provide functionality via reusable components.

2. Cross-functional teams <br/>
The microservices software design assigns developers to cross-functional teams where each team develops one/more microservices, and the team maintains each from start to finish.

3. Ownership over the product lifecycle <br/>
Each microservice team is responsible from UX design to frontend, backend, deployment and maintenance of the service.

4. Design for failure <br/>
A microservice application is composed of several microservices, and the application needs to be designed to tolerate failure - keep operating when any component of the microservice becomes unavailable.

## Advantages and Disadvantages of Microservices
**Advantages**
- freedom of choice of software and hardware
- supports distributed development
- better scalability
- faster development cycles
- isolated services easier to debug and maintain

**Disadvantages**
- hard to maintain without automation and advanced project management practices such as Agile
- adopting the methodology has a steep learning curve
- additional security issues 

## Where could it be useful?
Large enterprises such as Amazon, Netflix, Uber and Etsy use microservices to achieve scaling advantages, business agility and profitability.
