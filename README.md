# StoopidScript

 Its like my stoopid language, except its nothing like it.

### Installation
you need to have python >= 3.10 installed, then you can just run it with `python stoopidScript.py <path to file>`
### The available commands are

- var <type> <name> = <value>
- out <value>
- outln <value>
    - out and outln can use * to print all variables for debugging purposes
- if <condition>{  
    \<code>  
 }  
- goto <line>

### the variable types are:
- int  
- float  
- str
- bool  
- dynamic
    - type can change on the fly
- auto  
    - sets the type according to the initial declaration
- label  
    - if no value is set, it is set to the current line
    - used for goto