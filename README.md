# Software-Design-Document-Template

## 1. About
• What is the software application or feature?
• Who’s it intended for?
• What problem does the software solve?
• How is it going to work?
• What are the main concepts that are involved and how are they related?

## 2. User Interface
• What are the main user stories (happy flows + alternative flows)?
• If you’re adding a new feature to an existing software application, what impact does the feature
have on the overall structure of the interface? (e.g. are there big changes in the organization of
menus, navigation, and so on?)

## 3. Technical Specification
• What technical details need developers to know to develop the software or new feature?
• Are there new tables to add to the database? What fields?
• How will the software technically work? Are there particular algorithms or libraries that are
important?
• What will be the overall design? Which classes are needed? What design patterns are used to
model the concepts and relationships?
• What third-party software is needed to build the software or feature?

## 4. Testing and Security
• Are there specific coverage goals for the unit tests?
• What kinds of tests are needed (unit, regression, end-to-end, etc)?
• (new feature only) Are there any potential side-effects on other areas of the application when
adding this feature?
• What security checks need to be in place to allow the software to ship?
• (new feature only) How does the feature impact the security of the software? Is there a need for
a security audit before the feature is shipped?

## 5. Deployment
• Are there any architectural or DevOps changes needed (e.g. adding an extra microservice,
changes in deployment pipelines, adding secrets to services)?
• Are there any migration scripts that need to be written?

## 6. Planning
• How much time will developing the software or feature cost?
• What are the steps and how much time does step take?
• What are the developmental milestones and in what order?
• What are the main risk factors and are there any alternative routes to take if you find out
something isn’t feasible?
• What parts are absolutely required, and what parts can optionally be done at a later stage? (i.e.
the Definition of Done)

## 7. Broader Context
• What are limitations of the current design?
• What are possible extensions to think about for the future?
• Any other considerations?
