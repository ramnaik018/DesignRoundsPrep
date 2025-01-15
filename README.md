# General tips to keep in mind when starting off with design/machine coding interveiw.
## When ever you are given a problem statement , 
## There can be Two cases 
- **Aware of problem statement:**
    Ask if whats running on your mind is actuallay what is being expected from interveiwer.
    if yes, proceed with below steps.
- **Unaware of the problem statement**:
    Just ask for an Overveiw of that what is expected to be designed and what how it works.

- **Ask clarifying questions** (*You can always ask*)
  1. Do you just want me to design this particular system?
  2. Do you want to just design a particular entity or Do you want me to implement entire system?
  3. How will i interact with the user (will it be using REST API / Hardcode input/ Command Line)?
  4. Do you want me persist the data?
     - If yes, you need to choose Database and connect to it.
     - If not, you need to use in memory data base using some data structure.
    
  # Step1: Gathering and clarifying the requirements
  --- If the question is a single line statement , ofcourse we should gather the requirments and make a PRD. Else if we already have a PRD given , we can directly jump to clarifying the requirements.
  **Below are the steps to build a PRD :**
    1. suggest ideas/features and ask if they are required? (5-8 features)
        - To get Ideas try to visualise what the products lifecyle looks like and what it does.
        - Dont try to be oversmart and suggest basic requirements for a **minimum viable product** which you can do.
## **To better understand the steps mentioned, i have attached the Requirement gathering parts and designing taking few examples**
- **Design a Pen**
- **Design Tic Tac Toe**
- **Design Parking Lot**
- **Design BookMyShow**
- **Design Splitwise**

**Once done with gathering requirements and clarificaions, we can start with Class Diagrams:**
# Class Diagrams

1. **By visualising the requirement/entity**
  - we can start visualising the product from outside to inside OR inside to outside
3. **By identifying the nouns in the PRD**

## TIPS:
- **we should identify the classes and interface that can be derived form the PRD**
- **we should also be able to identify the ENUMS and if at all any design patterns that can be used**
- If at all in near forseeable future , if a noun can have other properties that should also be addressed , we can create a class(enitity) for that
- Or else if we can decide that current property is something that dosent need any other sepecifications , we can create a ENUM for that.
- If we have something that has subtypes , then its better to relate them via inheritance , we can also make parent classes as abstract or
interface to force child classes to have basic features of products (*if some parent is an entity , then its better to make it abstract class and if something
behaviour then its better to make it interface*).
- When we try to relate one class to another using UML class diagrams ,(composition or aggregation) - we should be able to justify to the interveiwer if one thing exists without another or not.

























