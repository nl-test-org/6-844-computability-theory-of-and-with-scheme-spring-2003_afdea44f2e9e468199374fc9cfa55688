---
course_id: 6-844-computability-theory-of-and-with-scheme-spring-2003
layout: course_section
menu:
  leftnav:
    identifier: 96f115069aa85ad74f89a2b9bdffef4b
    name: Calendar
    weight: 20
title: Calendar
type: course
uid: 96f115069aa85ad74f89a2b9bdffef4b

---

[Scheme software](http://www.gnu.org/software/mit-scheme/) is required to run the .scm files in this section.

This calendar shows the weekly schedule for the course, which usually includes three lecture and group problem solving sessions per week. This calendar provides links to course notes, problem sets, and other relevant resources. These materials are also provided separately in the [readings]({{< baseurl >}}/sections/readings), [assignments]({{< baseurl >}}/sections/assignments), and [tools]({{< baseurl >}}/sections/tools) sections of this course.

Week 1
------

_Wednesday_ (_First day of class_)

*   Course overview; no notes

Week 2
------

### Readings

*   Notes 1: Proving Arithmetic Equations, pp. 1–6 ([PDF]({{< baseurl >}}/sections/readings/aeqn))

### Assignments

*   Due at the end of Week 2:
    *   Download [Scheme](http://www.gnu.org/software/mit-scheme/)
    *   Download Scheme Continuation Interpreter project (Project 3 from 6.001 Fall '02) and submit solutions to Problems 11, 12 and 13
        *   A description of continuations ([PDF]({{< baseurl >}}/sections/assignments/continuations))
        *   Project 3 description ([PDF]({{< baseurl >}}/sections/assignments/project3))
        *   Project 3 code
            *   c-eval.scm ([SCM](/coursemedia/6-844-computability-theory-of-and-with-scheme-spring-2003/53d0a6f4b47606cc5779734692f1ee11_ceval.scm))
            *   desugar.scm ([SCM](/coursemedia/6-844-computability-theory-of-and-with-scheme-spring-2003/feeec1a09b94ab04506be8098cda4278_desugar.scm))
            *   meval.scm (Optional) ([SCM](/coursemedia/6-844-computability-theory-of-and-with-scheme-spring-2003/18eccb957a94b4f393b480a10ca5d4f5_meval.scm))

### Monday

*   Diagnostic Questionnaire ([PDF]({{< baseurl >}}/sections/assignments/diagnostic)) and Solutions ([PDF]({{< baseurl >}}/sections/assignments/diagnosticsol))

### Wednesday

*   Problems on arithmetic equations

### Friday

*   Problems on implementing catch/throw with call-cc

Week 3
------

### Readings

*   Notes 1: Proving Arithmetic Equations, final sections ([PDF]({{< baseurl >}}/sections/readings/aeqn))

### Wednesday

*   Procedure to check a linear proof and convert between linear and tree proofs

### Friday

*   Exercise: Convert a tree proof to a substitution proof ([PDF]({{< baseurl >}}/sections/calendar/subst_proof))
*   Scheme code ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/mccamanttreeproof.scm)) for the conversion
*   Arithmetic inequalities
*   Pattern matcher match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm))

Week 4
------

### Readings

*   Pattern matcher match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm))
*   Pattern-match based procedure proof-match.scm  ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/proofmatch.scm)) for converting a sequence-of-equations proof into a tree proof
*   Notes 2: Substitution into Arithmetic Expressions ([PDF]({{< baseurl >}}/sections/readings/subst))
*   Also, from last week, see Scheme code for converting a tree proof to a substitution proof ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/mccamanttreeproof.scm))

### Monday

*   Structural induction proof of the Substitution Lemma and Soundness of Substitution Proofs (see Notes 2: Substitution into Arithmetic Expressions ([PDF]({{< baseurl >}}/sections/readings/subst)))
*   Intro to pattern matching, with pattern-match based procedure proof-match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/proofmatch.scm)) for converting a sequence-of-equations proof into a tree proof

### Wednesday

*   Review of Notes 2: Substitution into Arithmetic Expressions ([PDF]({{< baseurl >}}/sections/readings/subst))
*   Problem for Friday: We extend Arithmetic Expressions with another case called an application
*   "Doctor" program using unnested matching eliza.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/eliza.scm))

### Friday

*   Discussion of using match/rewrite rules to put arithmetic expressions (possibly extended with applications and a derivative operator) into canonical form. An example is in deriv-simplify-rules.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/derivsimplifyrules.scm)); this version uses the alphabetized sum-of-monomials canonical form rather than the one-variable-polynomial-with-polynomial-coefficients canonical form of the Notes
*   Intro to Scheme Substitution Model

Week 5
------

### Readings

*   Notes 3: A Scheme Substitution Model, Sections 1–6 (pp. 1–14) ([PDF]({{< baseurl >}}/sections/readings/submodel))
*   Skim the scheme programs implementing the [Scheme Substitution Model]({{< baseurl >}}/sections/tools)

### Monday

*   Bring your laptop loaded with the [files]({{< baseurl >}}/sections/tools) for running the Substitution Model
*   Observe the submodel running on expressions in test-submodel.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/testsubmodel.scm))

### Wednesday

*   Discussion of control contexts in the Substitution Model

### Friday

*   Further example file for Substitution Model evaluation politician.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/politician.scm))

Week 6
------

### Readings

*   Notes 4: Term Models ([PDF]({{< baseurl >}}/sections/readings/term_models))

### Assignments

*   Due on Monday of Week 7: Problems 1–3 in Notes 4: Term Models ([PDF]({{< baseurl >}}/sections/readings/term_models))

### Monday

*   Trivial decision procedure: Two terms are equal in all models iff they are identical
*   Proving it: Introduction to term models

### Wednesday

*   Equational completeness theorem: If an equation follows logical from a set of equations, then the equation is provable using standard rules starting with the set of equations as axioms. Outline of proof using a term model

### Friday

*   Introduction to simple types

Week 7
------

### Monday

*   Environment models for simple types

### Wednesday

*   Combinator formulation of environment models

### Friday

*   Term models for simple types

Week 8
------

### Assignments

*   Due on Monday of Week 10: Problem Set 1 ([PDF]({{< baseurl >}}/sections/assignments/pset1))

### Monday

*   Compiling Scheme to register machines with a memory array

### Wednesday

*   Reducing RegM's with a memory array to 2-Counter machines

### Friday

*   Semigroup word problems: Rewrite rules for 2-CM simulation

Week 9
------

### Monday

*   Semigroup word problems: Confluence implies equations capture one-way rewrite rules for 2-CM simulation
*   Diamond Lemma for confluence

Week 10
-------

### Assignments

*   Due at the end of Week 10: Problem 18 from Notes 5: Scheme Computability, Part I ([PDF]({{< baseurl >}}/sections/readings/computability))

### Monday

*   Computability on S-expressions

### Wednesday

*   Notes 5: Scheme Computability, Part I ([PDF]({{< baseurl >}}/sections/readings/computability))

### Friday

*   Proof that productivity inherits up many-one reducibility (≦m). Further properties of ≦m

Week 11
-------

### Wednesday

*   Notes 7: Counter Machines ([PDF]({{< baseurl >}}/sections/readings/counter_machines))
*   Notes 8: Semigroup Word Problems ([PDF]({{< baseurl >}}/sections/readings/semigroups))
*   Notes 9: 1st-order Theory of Concatenation ([PDF]({{< baseurl >}}/sections/readings/concatenation))

### Friday

*   Notes 3: Scheme Substitution Model ([PDF]({{< baseurl >}}/sections/readings/submodel))
*   Notes 5: Scheme Computability, Part I ([PDF]({{< baseurl >}}/sections/readings/computability))
*   Notes 6: Scheme Computability, Part II ([PDF]({{< baseurl >}}/sections/readings/comput2))

Week 12
-------

### Assignments

*   Due on Wednesday of Week 13: Final Problem Set, 6 of these 10 problem:
    *   Notes 3: Scheme Substitution Model ([PDF]({{< baseurl >}}/sections/readings/submodel)), Problems 2, 13 (which is more appropriately **a** term project ([PDF]({{< baseurl >}}/sections/assignments/projects))), 14
    *   Notes 5: Scheme Computability, Part I ([PDF]({{< baseurl >}}/sections/readings/computability)) , Problem 21 – not Problem 22; Problem 22 can be a term project ([PDF]({{< baseurl >}}/sections/assignments/projects))
    *   Notes 6: Scheme Computability, Part II ([PDF]({{< baseurl >}}/sections/readings/comput2)), Problems 1, 5, 6, 7, 8, 9

### Monday

*   Course projects ([PDF]({{< baseurl >}}/sections/assignments/projects))

### Wednesday

*   Halting Problem for 2-Counter Machines  
    ≤m Th(∑\*, ·)  
    ≤m Th({1,2}\*, ·)  
    ≤m Th(N,+,×, ≦)  
    ≡m Th(Z,+,-, ×, ≦),

where Th(_M_) denotes the 1st-order formulas valid in model _M_

### Friday

*   Complete proof that \[2-CM Halting Problem ≤m Th(∑\*, ·)\]
*   Observe that Halts reduces to the set of closed formulas of the form ∃_z_.G where all quantifiers in G range over subwords of _z_

Week 13
-------

### Assignments

*   Due at the beginning of this week: Course project ([PDF]({{< baseurl >}}/sections/assignments/projects)) proposals

### Monday

*   Topic: Diophantine sets over the integers and naturals; closure under intersection. Primes ≠ range(_g_) for any polynomial, _g_

### Wednesday

*   MINScheme ≡T Halts. Sketch of relative computability: The jump operation

### Friday

*   Diophantine Predicates closed under ∧, ∨, ∃, but not ¬ (negation)
*   A Diophantine polynomial whose nonnegative range is the nonprimes

Week 14
-------

### Assignments

*   Due at the end of this week: Term project ([PDF]({{< baseurl >}}/sections/assignments/projects))

### Monday

*   Excerpt: pp. 174–181 on Undecidability of Exponential Diophantine Polynomials, from Jones, Neil D. "Computability and Complexity: from a Programming Perspective," MIT Press, c. 1997, 466pp.

### Wednesday (Last class)

*   Term project