Proposed Apigility Documentation
================================

- Installation
- Dependency injection of controllers/resources
- Terminology
    - Entity
    - Collection
    - Resource
    - Controller
    - InputFilter
    - ???
- Information on RESTful APIs:
    - What is REST?
    - What are the problems with implementing REST using JSON? (e.g., linking,
      embedded resources, etc.)
    - What is HAL?
    - How is error handling accomplished?
    - What is the Problem API for HTTP Services? (ApiProblem)
- Information on RPC
    - What is RPC?
    - How is RPC implemented in Apigility?
    - How can you return HAL from an RPC service?
- Document each module
    - zf-development-mode
    - zf-api-problem
    - zf-hal
    - zf-content-negotiation
    - zf-content-validation
    - zf-mvc-auth
    - zf-oauth2
    - zf-rest
    - zf-rpc
    - zf-versioning
    - zf-apigility-admin (the admin API, specifically)
- Advanced ACL usage
    - How to add to the ACL
    - How to inject the ACL into an RPC controller or REST resource
- Advanced InputFilter usage
    - Accessing the request’s input filter in an RPC controller via the MvcEvent
    - Accessing the request’s input filter in a REST resource via getInputFilter()
    - Injecting a named input filter into an RPC controller or REST resource
- Advanced Authentication/Authorization
    - The Authentication and Authorization events
    - Identities
    - How to add your own authentication and authorization listeners (and how
      they can circumvent the defaults)
    - OAuth2 strategies
    - Accessing the Identity via the MvcEvent
    - Accessing the Identity via the REST resource getIdentity() method
