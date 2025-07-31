
- **Monolithic Architecture** - Application is built as a single, indivisible unit. Run a **single** process. On a **single** server.
    
    **Challanges for monolithic architecture:**
    - Scalability
    - Lack flexibility with respect to techologies
    - Fixing issues can break another components
    - Deployment

- **Layered Architecture ( Modular Monolith) -** Layered architecture project can have a single solution and for logical separation, multiple projects.
    
    **Challanges for layered architecture:**
    
    - Limited Scalability
    - Lack of flexibility
    - Deployment as a single server

- **Tiered Architecture -** Application is divided into physical layers and deployed on multiple hosts
	![[Pasted image 20250731092324.png]]
	
	**Challanges of Tired Architecture**
	- Compexity
	- Scalability
	- Maintenance and Upgrades
	- perforamce
	- Fault Isolation
	- Communication and Synchronization
	- Security
	- Testing and Debugging

- **Microservices Architecture -** Structures an application as a collection of small, independent, and loosely coupled services. Each service focuses on a specific business capability and can be developed
    
     **Benefits of Microservices Architecture**
    - Modularity and scalability
    - Independent Development and Deployment
    - Fault Isolation and Resilience
    - Flexibility and Technology Diversity
    - Improved Scalability and Performance
    - Сontinuous Deployment and Devops Practices
    - Improved Maintainability and debugging
    - Enhanced Team Autonomy and Scalability
    
    **Project fit for Microservices Architecture**
    
    - Fast developing web and business apps
    - Large and Complex Systems
    - Project which needs scalability and high demand
    - Project which has independent and autonomous teams
    - Project which needs Heterogeneous Technology
    - Continuous Deployment and Devops Practices
    
    **Challenges of Microservices Architecture**
    
    - Distributed System Complexity
    - Service Coordination
    - Data Management
    - Service Dependencies
    - Operational Complexity
    - Service Discovery and Load Balancing
    - Security and Authentication
    - Organizational Challenges
    - Monitoring and Observability
- **Serverless Architecture -** your code will run on some third-party vendors server infrastructure which you don’t need to worry about ,it does not mean that there is no server to run your code logic rather you do not need to maintain it.that is the business of third-party vendors like Microsoft Azure, AWS and Google etc.
    
    **Benefits of Serverless Architecture**
    
    - No server management is required
    - Pay- per-use pricing
    - Automatic scaling
    - Faster deployments and updates
    - Improved security
    - Increased agility
    - Improved focus on innovation
    - Reduced costs
    
    **Types of Cloud Comptuing / Cloud Services**
    
    - Infrastructure as - a- Service ( IaaS) - Procure the infrastructure over the cloud and make it ready per your requirements. Its like a renting virtualized resources from a cloud provider. You have control over the operation system, middleware, runtime environment, applications.
    - Platform-as-a-Service (PasS) - offers a complete development and deployment platform. Provides a pre-configured environment to build, test, and deploy applications
    - Software-as-a-Service (SaaS) - Accessing software applications or services hosted and managed by a third-party provider.
    - Faas
    
    **How to make a serverless architecture?**
    
    > **MYTH: Severless architecture its NOT MEAN that its a simply deploying your application on cloud**
    
    Here we need to use FaaS ( AWS Lambda, Azure Functions, Google Cloud Functions)
    
    **Challenges of Severless Architecture**
    
    - Vendor Lock-In
    - Limited Execution Time
    - Cold Start Latency
    - Testing and debugging

- **Event-Driven Architecture -** structures an application around the production, detection and consumption of events. Decoupling the components by establishing loose coupling and asynchronous communication. Develop application components separately and make them produce and consume and process the events accordingly.
    
    **How to implement:**
    
    - Indentify the events
    - Define event sources
    - Choose an event-driven framework ( Kafka , AWS Lambda, Azure Event Grid and etc )
    - Design event producers
    - Implement event consumers
    - Define Event Schemas
    - Ensure event reliability
    - Scale and monitor
    
    **Benefits:**
    
    - Loose Coupling and Flexibility
    - Scalability and Performance
    - Real-time Responsiveness
    - Modularity and reusability
    - Event Sourcing and Auditability
    
    **Challenges of event-driven Architecture**
    
    - The complexity of event flow
    - Eventual Consistency
    - Event Choreography and Orchestration
    - Event Durability and Reliability