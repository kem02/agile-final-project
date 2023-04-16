---
name: User Story
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** User
 **I need** a service that has a counter   
 **So that** I can keep track of how many times something was done
   
 ### Details and Assumptions
 * Need a way to increment a counter
 * Need a way to get the current value
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given I have incremented the counter to 2
 When I make a call to get the current value
 Then it should return 2 as a counter value
 ```
