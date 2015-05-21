# Lua

##About Lua

* Lua is a scripting language. 
* It is highly extensible due to its libraries.
* It can be used as a glue language, to glue components written in other languages like C/C++.
* Low level, performance critical and less frequently modified components should be written in C/C++. 
* Frequently modified components can be written in Lua. 
* Unlike other glue languages, Lua is also a full fleged language. 

Features:          
 1. **Extensiblility**: Lua can be extended using libraries written in Lua and C.        
 2. **Simplicity**: Lua can be easily learnt, as it has only a few, but powerful, concepts.        
 3. **Efficiency**: Lua is one of the fastest scripting languages, according to benchmarks.        
 4. **Portability**: Lua can be run on any platform. All you need is an ANSI C compiler.         
 
* Lua can be embedded in an application. The user can write new functions in Lua to provide new features.
* Lua can also be stand-alone projects, which use much text-processing.
* Some people use C and Lua together, they use Lua as a C library. 

##Basics

###Basics

* Save the following in a file called "hello.lua":          
 
	print("Hello World")
	
* Type the following to run it:                    

	%lua hello.lua

* The following program "factorial.lua" asks the user for a number and calculates its factorial.                  

	--defines factorial function       
	function fact(n)           
		if n == 0 then            
			return 1            
		else           
			return n * fact(n-1)          
		end              
	end                   
	
	print("enter a number:")            
	a = io.read("*n")			--reads a number           
	print(fact(a))		

* 
	
	
