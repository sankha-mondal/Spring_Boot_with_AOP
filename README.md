# Spring_Boot_with_AOP
Aspect Oriented Programming (AOP) compliments OOPs in the sense that it also provides modularity. But the key unit of modularity is aspect than class.  AOP breaks the program logic into distinct parts (called concerns). It is used to increase modularity by cross-cutting concerns.

# Spring AOP : Aspect Oriented Programming :

Procedure Language 

Limitation of Procedure Oriented Programming language 
In Procedure oriented language we will focus more than functionality or coding rather 
than properties or state.

Object oriented langauge we will focus on properties or state. 

# AOP focus on functionality. 

Generally while writing functionality or logic the code divided into two parts. 
1. core functionality or primary functionality or atual coding for that application.  
2.  secondary functionality or the functionality which is common on all application or 
which will support to develop the application or cross cutting is known as secondary functionality 
according to AOP. 


	Banking application:- 
	a. Check Balance 
	b. transfer the amount 
	c. withdraw 
	d. deposit 
	
	etc 

	Secondary functionality:-
   	a. login 
	b. database connectivity 
	c. security 
	d. validation 
		
	etc 

	AOP allow separation of the cross cutting concern. 

	These are cross cutting concern are different from the main business functionality. 
	

# AOP Terminology 
--------------------
1. Aspect : An aspect is a module that encapsulated adivce and pointcuts and provide cross cutting for our application. 
2. Point cut : A point cut is an expression language that selects one or more join points where advice will execute.
3. joint point : A join point is a point in the application were we can apply an AOP advice. 
4. Adivce : The advice is an action that we will excecute before or after the method or business method execution. 
	advice divided into 5 types 
	a. before 
	b. after 
	c. around (combination of before and after)
	d. afterthrow (if any exception generate)
	e. afterReturning 
		
	 
