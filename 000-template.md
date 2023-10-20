* Name: RFC Template
* Start Date: 2023-10-20
* RFC PR: https://github.com/web-infra-dev/rfcs/pull/1
  
# Summary
One sentence/paragraph explanation of the RFC, i.e. What's being proposed?
e.g. Adding a new API X for doing Y, so that ...

# Motivation
Why are we doing this? What problem does it solve? What is the expected outcome?
Please focus on explaining the motivation so that if this RFC is not accepted, the motivation could be used to develop alternative solutions. In other words, enumerate the constraints you are trying to solve without coupling them too closely to the solution you have in mind.

# Usage Explanation 
Explain the solution being proposed and assuming you are writing the official documentation: think about this as explaining the proposal as if it was already implemented in Rspack and you were teaching it to the users (for user-facing APIs) or Rspack contributors (for internal-oriented RFCs). 
This generally means:
- Introducing these new or changed APIs and concepts. What are the expected behaviours?
- Explanining the changes in terms of code examples and how people should think about it.
- Does it introduce any compatibility issues or breaking changes? If applicable, provide sample errors, deprecation warnings, or migration guidance.

# Drawbacks & Challenges
There are tradeoffs to choosing any path. Why should we not do this (What are the cons of doing this)?
Please consider:
- implementation cost, both in terms of code size and complexity
- whether the proposed feature can be implemented in user space
- integration of this feature with other existing and planned features
- cost of migrating existing Rspack applications (is it a breaking change?)

# Rationale & Alternatives 
Is there any other way to solve this problem? What is the rationale for not choosing them? 
Remember that "not doing something" is also a choice. What is the impact of not doing this? 

# Request For Feature Area Owners
Outlines all the area owners that will be involved in reviewing this RFC.

# Detailed Designs
This is the bulk of a full RFC. Explain the design in enough implementation detail:
- It should be reasonably clear how the feature would be implemented. You may use pseudo code, interface declarations, architectural diagrams, etc., to answer "how to make this happen? "
- Its interaction with other features is clear.
- Corner cases are dissected by example.
We encourage (we know this can be difficult and demanding) you to think this as writing something as formal as a design doc or a technical specification. You may include any supportive materials, e.g. the interface/header declarations, architectural diagrams, flow charts, class diagrams to describe your design.

# Unresolved Questions & TODOs
Optional, What parts of the design are still TBD?

# Prior Arts & References
Discuss prior art, both the good and the bad, in relation to this proposal. This section is intended to encourage you as an author to think about the lessons from other similar technologies, provide readers of your RFC with a fuller picture.