## Basics
```sh
1. What is "N + 1" problem in REST APIs and how would you solve it?
   Solution:
	    N + 1  problem is mostly talked in context of ORMs. The application needs to load N
	    children of a parent entity where only the parent entity was requested for.
	    by dafault ORMs are configured with lazy-loading enabled.Include more information in
	    individual resources inside collection resource.
```

```sh
2. When do you stop writing unit tests?
   Solution:
	    Unit tests are uses for functionality where return statetement changes based on input.
	    if functinality have static return value or fixed no of value.
	    A control statement which return 0 doesn't need to be tested.
	    its dificult to wirite for UI.
```
```sh
3. Why would one use monorepos?
   Solution:
	    A monorepo is a single repository that stores all of your code and assets for every project.
            It creates a single source of truth.It makes easier to share code also easier to refactor code.
            It used with microservices.
	    One place to store all configs and tests.
	    Easily refactor global features with atomic commits.
            Simplified package publishing.
            Easier dependency management.
            Re-use code with shared packages while still keeping them isolated.
```
```sh
4. What is Liskov substitution principle?

   Solution:
            The Liskov substitution principle is the 3rd of Rober C Martin's famous SOLID design
	    Principle. SOLID 
            S: Single Reponsibility Principle
	    O: Open/Closed Principle
            L: Lisko Substitution Principle
            I: Interface Segregation Principle
            D: Dependency Inversion
```
```sh
5. How do you avoid race conditions?

   Solution:
	    To prevent race conditions from occuring you must make sure that the critical section is executed as an atomic instruction.
	    That means that once s single threaded is executing it no other threads can execute it until the first thread has left the critical 
	    section.
```
```sh
6. What is the first thing you do when you encounter a bug?
   Solution:
	    Review the code why bug occurs.Cross check the at what condition bug is comming.
```



## "Why would anyone do drugs when they can just mow a lawn?"
```sh
> For this challenge, user authentication is **not** required. There is no time limit. Assume that the frontend is handled by another developer.

- **Language**: _JavaScript_ (TypeScript is preferrable, but not required)
- **Framework**: _NestJS_
- **Database**: _MongoDB_
```
```sh
Hank likes to mow the lawn. Back in the day, he would offer his services to his neighbors for a fee. Now, he wishes to start a company around this.
As his friend, he asked if you can help him digitize the business. Users would register on the website, then book visits from their dashboard. 
One of the requirements he specified is to have scalable pricing; 
To mow 1 square metre, the client will have to pay £1. 
If the area is bigger than 15 square metres, a discount of 10% will be applied. 
If the area is bigger than 25 square metres, a discount of 15% will be applied. 
To acquire new clients, Billy wants to have a coupon system in place as well.


Solutions:
	 I have not understand the statement.

```
```sh
## Future of lawn mowing endeavours

> This section has no correct answers. Albeit optional, your answers will help us understand your thinking process.

1. What other features would you like to add?
2. How would you handle user authentication?
3. How would you deploy the solution in an enterprise environment?
```
