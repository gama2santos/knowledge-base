- Start Date: (fill me in with today's date, YYYY-MM-DD)
- Members: (fill me with the names of the RFC creators)
- RFC PR: (leave this empty)

# Summary

Brief explanation of the feature.

# Basic example

If the proposal involves a new or changed API, include a basic code example.
Omit this section if it's not applicable.

# Motivation

Why are we doing this? What use cases does it support? What is the expected
outcome?

Please focus on explaining the motivation so that if this RFC is not accepted,
the motivation could be used to develop alternative solutions. In other words,
enumerate the constraints you are trying to solve without coupling them too
closely to the solution you have in mind.

# Detailed design

This is the bulk of the RFC. Explain the design in enough detail for somebody
familiar with React to understand, and for somebody familiar with the
implementation to implement. This should get into specifics and corner-cases,
and include examples of how the feature is used. Any new terminology should be
defined here.

# Drawbacks

Why should we *not* do this? Please consider:

- implementation cost, both in term of code size and complexity
- whether the proposed feature can be implemented in user space
- the impact on teaching people React
- integration of this feature with other existing and planned features
- cost of migrating existing React applications (is it a breaking change?)

There are tradeoffs to choosing any path. Attempt to identify them here.

# Alternatives

What other designs have been considered? What is the impact of not doing this?

# Detailed design

Model C4 Placement Diagram

![C4 Model Places!](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6e636099-4162- 46dB-b49a-232f34ac3cf4%2Fc4-notificationsTeam.png?table=block&id=52cfaea3-b036-400f-86ef-097f0efdacef and SpaceId=ed752afe-7a09-4db1-a4e5-a1660f831484 and width=2,000 and userId4f12=473-d4f12 5 and width=2,000 userId4f12 401c-8082-755f4372089c and cache=v2)

To implement this tool, we need the user to have an active login, later the implementation of the notifications will be done automatically depending on what the user is looking for and what is of interest to them.

I think that in order to carry out the project we can use Server sent event (SSE) although we debate among ourselves that there is a disadvantage.

![Server sent event (SSE)]
(https://javascript.info/server-sent-events)

We will leave it pending an evaluation by the project managers.

# How we teach this

What names and terminology work best for these concepts and why? How is this
idea best presented? As a continuation of existing C9 projects patterns?

Would the acceptance of this proposal mean the C9 documentation must be
re-organized or altered? Does it change how C9 is taught to new developers
at any level?

How should this feature be taught to existing C9 developers?

# Adoption strategy

The fact of the notifications has repercussions for some other teams of the project, I think it is essential that the front-end and the back-end work together to be able to do a good practice.

An intelligent architecture and a correct communication will help that.

# Unresolved questions

What development alternatives will be the most suitable?

Will our team be able to implement it?

How much will notifications affect other teams and parts of the project?

What we will use to make the project safe and provide a good user experience
