## Hi there 👋

Mampfio is a fictional food-delivery platform and a teaching codebase for the Self-contained Systems (SCS) architecture style. 
The domain is split into five bounded contexts: Discovery, Ordering, Restaurant-Backoffice, Delivery and Ratings. 
Each one is built as its own system with its own application, database and UI, and no code is shared between them. 
The systems mostly talk to each other through links, HTML transclusion and asynchronous HTTP Feeds with CloudEvents, 
and use synchronous calls or messaging only where a specific trade-off calls for it. 

Mampfio is meant for learning, not for production.
