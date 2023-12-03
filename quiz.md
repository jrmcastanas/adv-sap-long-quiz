## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- SOA is a way of making software by using existing pieces or services that can be used again for different apps. It also lets different systems or apps talk to each other through a common interface.

2. List and discuss the characteristics of SOA.
- Standardized Service Contracts - This is a rule we follow when we make services so that they can work well with other services in the same group. The contracts also tell us what the service can do and what it wants from us.

Loose Coupling - This is a way of making services independent from each other, so that they can change without messing up the users who rely on them.

Abstraction - This is a way of hiding the technical details of a service and focusing on the business process it supports. This makes the service more flexible and adaptable.

Reusability - This is a way of avoiding doing the same thing twice and wasting resources by using existing services whenever possible, or making new services that can be used for multiple purposes.

Autonomy - This is a way of giving services the power and control to make their own decisions, without needing permission or interference from others.

Statelessness - This is a way of reducing the amount of information a service needs to remember or store, so that it can work better and faster.

Discoverability - This is a way of making services easy to find and understand by providing metadata that describes their purpose and capabilities to humans and systems.

Composability - This is a way of solving complex problems by breaking them down into smaller and simpler parts, and using services to combine them.

Interoperability - This is a way of making services compatible and able to share data with each other, by following common standards and protocols.

3. Define Microservices.
- Microservices are like SOA, but they are used to make apps that can grow and recover more easily. They are like Lego pieces that can be put together in different ways to make bigger apps. Microservices are small, independent parts that work together through a common interface. 

4. List and discuss the benefits of using Microservices.
- Independently deployable - This is the main feature of microservices, which means that each service can be deployed separately without affecting the others. The services are small and communicate with each other through networks, and this gives us more options to solve the problems we encounter.

Right tool for job - This is one of the advantages of using microservices, which allows us to use the best tool for each task. Microservices can store and process more data by breaking it into smaller pieces, and each service can use its own language and framework to communicate with the application we want.

Precise Scaling - With microservices, we can deploy and scale each service individually and precisely. This means that we can handle a large number of tasks at the same time, and do it efficiently and accurately.

5. List and discuss the similarities and differences of SOA and Microservices.
- Similarities Reuse - Both SOA and Microservices try to avoid making new services when there are already ones that can be used again. SOA looks for available services, while Microservices copy and paste code and don’t mind having the same data.

Synchronous calls - Both SOA and Microservices use synchronous protocols to make their services available across the enterprise. But, Microservices only use synchronous calls when they need to wait for another service’s answer before moving on.

Data duplication - Both SOA and Microservices have collections of services that do specific things. They also have to deal with complex data synchronization patterns because of data duplication.

Differences between SOA and Microservices

Communication - SOA uses an Enterprise Service Bus (ESB) to handle communication between services, but this can be a problem for the whole enterprise if one service slows down. Microservices use simpler messaging systems like APIs that enable faster communication and are developed independently with their own communication protocols.

Interoperability - SOA sets standards for services to share data and make sure that they don’t get reduced. Interoperability means the ability of different software programs to exchange data. Microservices can also exchange and use information across systems, but they have more freedom and autonomy.

Service granularity - Microservices have very specialized services that do one thing only, while SOA services can range from small and specialized to enterprise-wide and general.

Speed - SOA makes development and troubleshooting easier, but it also makes SOA work more slowly than Microservices. Microservices let developers work on small and independent parts of an app that can be quickly deployed and tested without affecting the rest of the app.

6. Define Web Services.
- Web services are a class of internet software that are made available for use by clients or other web-based programs from the web server of an application service provider. They are based on standardized messaging protocols.
Web services can range from major services like customer relationship management (CRM) or storage management to much more specialized services like providing a stock quote or comparing bids on an auction item. Application services is another name for the phrase that is occasionally used.

7. List and discuss the benefits of using Web Services.
- The benefits of using web services, is A web service seeks to transform the Internet from a purely visual tool to a value-based instrument. These application-to-application partnerships are motivated by and predicated on accepted ideas. A web administrator is a managed code that is typically started with HTTP queries and can be called remotely via HTTP. With web administrations, you can discover how useful your current code is across the system. When your program becomes available on the framework, other apps will be able to utilize its usefulness. 


8. List and discuss the characteristics of Web Services.
- XML Based
XML is used by web services for record transportation and information representation. Operating systems, platforms, or networking are not required when using XML. At their intermediate level, web-based applications are very interoperable.

- Loosely coupled
Loosely coupled connections between systems are supported by web services. Through a web API, it exchanges messages with each other in XML format. Web API gives the environment an additional layer of abstraction, which increases the connection's flexibility and adaptability.

9. List and discuss the distinct roles in Web Services Architecture.
- Additionally, the service provider has a network-associable module that creates and publishes a service description to the service registry or service requestor for the web service. The service description can be obtained locally or from the service registry by the service requestor using the find operation. In order to connect with the service provider and launch the web service implementation, it also makes use of the service description.

10. List and discuss the Web Services Components.
- Software systems known as web services are made to facilitate online communication between machines. They facilitate the sharing of functionality and data between various systems and apps. These are a few examples of the various kinds of web services. 
- SOAP (Simple Object Access Protocol)
Applications can exchange structured data by using the messaging protocol SOAP. In order to exchange data, it makes use of XML (Extensible Markup Language) and other communication protocols like SMTP or HTTP. Because it enables communication between various platforms and programming languages, SOAP is significant.
- REST (Representational State Transfer)
The HTTP protocol is used for data exchange in web services architectures that follow the REST style. It can be accessed with basic HTTP requests and communicates with clients via a standard interface. Because it offers a straightforward, scalable, and effective means of transferring data between systems, REST is significant.
