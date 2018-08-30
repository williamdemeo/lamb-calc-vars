## Notes on the paper "Applying universal algebra to lambda calculus" by Manzonetto and Salibra.

This paper is 

1. a survey of what is (or was, c. 2008) known about the lattice of all 
   **λ-theories** (= equational extensions of untyped λ-calculus) and the models of lambda calculus via universal algebra. 

   This includes the state of the art about open questions concerning representability of λ-theories as theories of models, and 26 open problems. 

2. a demonstration that lambda calculus and combinatory logic satisfy interesting 
   algebraic properties. 
   
   It is shown that the Stone representation theorem for Boolean algebras can be 
   generalized to **combinatory algebras** and **λ-abstraction algebras**. 

   In every combinatory and λ-abstraction algebra there is a Boolean algebra of 
   **central elements** (playing the role of idempotent elements in rings). 

   In the paper, the *central elements* are used to:
   
   a. represent any combinatory and λ-abstraction algebra as a weak Boolean product of
      directly indecomposable algebras (i.e., not a Cartesian product of two non-trivial algebras), and 
   
   b. provide applications of the representation theorem to lambda calculus. 

   The authors use the phrase **indecomposable semantics** to mean the semantics 
   of λ-calc given in terms of models of λ-calc that are directly indecomposable.

   It is shown that this indecomposable semantics includes the continuous, stable and strongly stable semantics, as well as the term models of all *semisensible* λ-theories. 
   
   In one of the main results of the paper it is shown that the indecomposable semantics is equationally incomplete, and this incompleteness is "as wide as possible."


A **λ-theory** is an equational extension of λ-calculus.  The set of all λ-theories is
naturally equipped with the structure of a complete lattice (See Ch 4 of [Bar-84]) with 
bottom element the least λ-theory λβ, and top element the inconsistent λ-theory.

Although researchers have mainly focused their interest on a limited number of them, the lattice
of λ-theories, denoted by λT, has a very rich and complex structure 
(see, eg, [Bar-84], [Ber-00], [Ber-06]).


The λ-calculus, although its axioms are all in the form of equations, is not a genuine
equational theory since the variable-binding properties of λ-abstraction prevent "variables"
in λ-calculus from operating as real algebraic variables. Consequently methods of universal
algebra for defining the semantics of an arbitrary algebraic theory, for instance, are not 
directly applicable. 

There have been several attempts to reformulate the λ-calculus as a purely algebraic theory. 
The earliest, and best known, algebraic models are the combinatory algebras of Curry and 
Schönfinkel. Although combinatory algebras do not keep the λ-notation, they do have a simple 
purely equational characterization and were used to provide an intrinsic first-order, but not 
equational, characterization of the models of λ-calculus, as a special class of combinatory 
algebras called λ-models [4, Def. 5.2.7].

The connection between the syntax and the semantics of lambda calculus is established by the
completeness theorem of lambda calculus: every λ-theory is the equational theory of some λ-
model (see [4]).
Semantical methods have been extensively investigated. Topology is at the center

+ [Bar-84] H.P. Barendregt. *The lambda calculus: Its syntax and semantics*. 
  North-Holland Publishing Co., Amsterdam, 1984.

+ [Ber-00] C. Berline. "From computation to foundations via functions and application: 
  The λ-calculus and its webbed models." Theoretical Computer Science, 249:81–161, 2000.

+ [Ber-06] C. Berline. "Graph models of λ-calculus at work, and variations." 
  Math. Struct. in Comp. Science, 16:185--221, 2006.
