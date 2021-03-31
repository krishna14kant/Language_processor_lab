# Two Pass Assembler
This project was created for Network Lab

## Pass 1
### Input :
    input.dat    
    optab.dat  
### Output :
    intermediate.dat  
    symtab.dat  

## Pass 2
### Input :
    intermediate.dat  
    symtab.dat  
    optab.dat
### Output :
    asmlist.dat  
    out.dat  


## Steps to execute
1. compile pass1.c and pass2.c to pass1 and pass2
2. run pass1 as `./pass1`
3. run pass2 as `./pass2`
4. See the output in out.dat
