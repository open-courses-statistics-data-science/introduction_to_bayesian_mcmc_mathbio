# A short introduction to Bayesian inference and MCMC
This course provides a short introduction to Bayesian inference, which should take roughly a day to complete.

By the end of the course, the participant should:

- Understand the goal of statistical inference.
- Appreciate how Bayesian and frequentist approaches to inference achieve this goal.
- Know the elements required to do Bayesian inference and appreciate how they affect inferences.
- Know why exact Bayesian inference is *hard* and that conjugate priors provide some remedy.
- Recognise how sampling can be used to understand a distribution.
- Know what is meant by Markov chain Monte Carlo (MCMC) and be able to code up their own version of Random Walk Metropolis — the foundational MCMC algorithm.
- Know how to judge convergence of MCMC algorithms.
- Understand how to formulate inference problems for ordinary differential equation and partial differential equation models.
- Understand how Approximate Bayesian Computation works.

The course consists of two lectures and problem sets.

## Prerequisites

The course assumes a basic knowledge of probability distributions and of a scientific programming language like R or Python.

## Morning material

The lecture is [here](https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/lectures/introduction_to_bayesian_inference.pdf). The problem sets for this morning are:

- [*Disease prevalence exercise*](https://htmlpreview.github.io/?https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/problem_disease_prevalence.nb.html). This example mirrors the material in the lectures and invites participants to estimate the prevalence of a disease. It goes through maximum likelihood estimation and Bayesian inference. The answers (written in R) to this problem set are [here](https://htmlpreview.github.io/?https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/answers/answer_disease_prevalence.nb.html).
- [*Epileptic seizure exercise*](https://htmlpreview.github.io/?https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/problem_epilepsy.nb.html). This example uses [real data](./problem_sets/data/conjugate_epil.csv) from a study of epilepsy (see this [paper](https://www.jstor.org/stable/2532086) for more information). The answers to the problem set are [here](https://htmlpreview.github.io/?https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/answers/answer_epilepsy.nb.html).

## Afternoon material

The lecture is large so will have been shared with participants. Alternatively the .tex file is [here](https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/lectures/introduction_to_mcmc.tex) if you would like to build it locally.

The problem set for this afternoon is [here](https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/mcmc_problems.pdf) and the answers are [here](https://github.com/ben18785/introduction_to_bayesian_mcmc_mathbio/blob/main/problem_sets/answers/mcmc_problems_and_answers.pdf). This problem set invites participants to code up their own version of a Random Walk Metropolis algorithm.

## Reference material

This course is short; the field of Bayesian statistics is large. As such, there are many things to read before / after the lectures.

### Reading

This course follows closely my book, "A Student's Guide to Bayesian Statistics", published by Sage, which is freely available on Oxford's SOLO as an online resource; I think the DTC also has copies available in the library.

The morning material covers elements of chapters 2, 4, 5, 6, 7 and 9.

The afternoon focuses mainly on chapter 12 and 13 but covers some material from chapters 14 and 15.

Another book I really like is [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) by McElreath, which goes into way more detail about *why* we do statistical modelling.

### Watching

Both [me](https://www.youtube.com/playlist?list=PLwJRxp3blEvZ8AKMXOy0fc0cqT61GsKCG) and [McElreath](https://www.youtube.com/watch?v=UgLF0aLk85s) have freely available YouTube series.