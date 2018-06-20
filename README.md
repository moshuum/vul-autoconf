# Autoconf Example

This project is an example of a project using GNU Autoconf to manage its build. This project uses a Makefile libraries.

`configure.ac` at the root directory that declare the library's directory to build and its dependency required. The library directory are:  
-  lib  

The dependencies are:  
- sqlite  
 
#### To build the projects:
`1. aclocal
2. automake --add-missing
3. autoconf or autoreconf
4. ./configure
5. make`


#### To run the projects:
`./src/HelloWorld`  

### Number of dependencies:  
- 1 direct dependency.  
- --- transitive dependency.  
- 2 vulnerabilities. 
  
#### Vulnerable Call Chain

#### What's next?




**building**  
1. aclocal
2. automake --add-missing
3. autoconf or autoreconf

**Instructions**  
1. ./configure
2. make  
3. ./src/HelloWorld
