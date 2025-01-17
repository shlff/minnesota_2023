# Advanced Dynamic Programming 

## Minnesota Fall 2023

* Lecturer: John Stachurski
* Dates: Mon Sept 11th -- Fri Sept 29th 


## Lecture times

* Mon: 8am--10am
* Wed: 9am--11am
* Fri: 9am--11am


## Topic

This is an advanced course on dynamic programming with a heavy dose of
computation.  The course is based on the book [Dynamic Programming](https://dp.quantecon.org/), which is free to download (and
forthcoming from Cambridge UP). Since the course is relatively advanced, I will
skim chapters 1 ~ 3 and less advanced students who wish to take the
course can read them more carefully in their own time.

Most of our focus will be on chapters 4 ~ 8.  Chapter 10 will probably be
omitted completely.

The lecture slides can be found in the `slides` directory.




## Assessment

Assessment will consist of five assignments.  All five are to be submitted as
individual Jupyter notebooks to <john.stachurski@anu.edu.au>, with the following exact naming
convention

    `firstname_lastname_assignment_x.ipynb`

where `x` is the assignment number.

All assignments must be in either Python or Julia.  In some assignments the
language and code libraries will be specified.

The schedule for the assignments is given below, in the syllabus.

Please note that you are *encouraged* to collaborate with a group of peers on
the assignments --- otherwise you will probably find the volume is too high. (If
you don't have anyone to collaborate with please tell me and I will try to
match-make.) However, after collaborating, you can probably gain extra marks by
adding personal finishing touches, such as cleaning, refactoring and documenting
code, adding explanations between code blocks, squeezing out a bit more speed by
modifying code, etc.


## Office hours

I am in office 4-117.

Office hours are 1pm -- 2pm Monday + Wednesday + Friday

You can set up appointments at other times via email <john.stachurski@anu.edu.au>.

## Syllabus



### WEEK 1  

#### Lecture 1 (Sept 11th)

1. Intro to the course / housekeeping
1. QuantEcon lecture: [Writing Good Code](https://python-programming.quantecon.org/writing_good_code.html)
1. Ch 0 slides 
1. Julia quick start  (`julia_quickstart.ipynb` in notebooks folder)
1. Assignment 1: optimal savings with Julia (due Friday 15th Sept)


#### Lecture 2 (Sept 13th)

1. Ch 1 slides --- highlights
    * Vector and matrix norms
    * Neumann series lemma
    * Banach's fixed point theorem
    * Job search: VFI
    * Job search: Continuation value method
1. Julia - Fortran - Python single thread horse race (`julia_numba_fortran_horse_race.ipynb` in notebooks folder)
1. Numba-based multithreading on the CPU (`numba_multithreading.ipynb` in notebooks folder)


#### Lecture 3 (Sept 15th)

1. Numba - NumPy - JAX multithreading comparison (`numba_numpy_jax_horse_race.ipynb` in notebooks folder)
1. QuantEcon lecture: [An Introduction to JAX](https://jax.quantecon.org/jax_intro.html)
1. Ch 2 slides --- highlights
    * Convergence rates
    * Nonnegative matrices
    * Perron--Frobenius theorem
    * Linear operators
1. Assignment 2: Ergodicity  (due Wed 20th Sept)






###   WEEK 2  


#### Lecture 4 (Sept 18th)

1. Ch 3 slides 
    * Markov chains: foundations
    * Discretization
    * Valuation (constant discounting)
    * Job search revisited
1. Ch 4 slides 
    

#### Lecture 5 (Sept 20th)

1. QuantEcon lecture: [An Asset Pricing Problem](https://jax.quantecon.org/markov_asset.html)
1. QuantEcon lecture: [Newton's Method via JAX](https://jax.quantecon.org/newtons_method.html)
1. Assignment 3:  Nonlinear asset pricing (due Mon 25th Sept)


#### Lecture 6 (Sept 22nd)


1. Ch 5 slides
1. QuantEcon lecture:  [Optimal Investment](https://jax.quantecon.org/opt_invest.html)







###   WEEK 3  

#### Lecture 7  (Sept 25th)

1. Ch 6 slides
1. Inventory SDD --- Julia version
1. Assignment 4: Inventory SDD (due Fri 29th Sept)

#### Lecture 8  (Sept 27th)

1. Ch 7 slides

#### Lecture 9  (Sept 29th)

1. Ch 8 slides
1. Assignment 5: TBD (due Friday 6th Oct)


