# Triangle-Compiler

Welcome to the triangle programming repo language a simple programming 
language for my final year compiler design module. This is to serve as 
documentation for my mini language.

The vocabulary of this language is as follows.

    arithmetic operators := [+ | - | / | * | %]
    
    relational operators := [< | > | == | <= | >= | !=]
    
    special symbols      := [( | ) | { | } | ;]
    
    identifier           := [(letter | _ | $)(letter | number | _ | $)*]
    
    keyword              := [if | for | begin | const | do | else |
                             end | if | in | let | while | then | var]
                             
    integer literal      := [(number)+]
    
    string literal       := [(\")(.)*(\")]
    
 A short primer on symbols used in the expressions above:
 
    + means match one or more characters
    
    . means match any character
    
    * means match zero or more characters
    
    | means or
 
 The project is made in java and its structure is as follows:
 
    