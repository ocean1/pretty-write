# PrettyWrite: Practical Thesis-writing Guidelines for Master Students

This work-in-progress document contains practical guidelines for writing
research-grade computer science theses for master students.

## Writing Guidelines for a Research Thesis

### Writing Guidelines

- get proficient with LaTeX (\documentclass{book} - don't ask for a template: you don't need one)
- we expect you to write in correct English
- read [this book](http://www.amazon.com/BUGS-Writing-Revised-Edition-Debugging/dp/020137921X/ref=sr_1_fkmr0_1?ie=UTF8&qid=1392997697&sr=8-1-fkmr0&keywords=lynn+dupree+debugging+prose)
- write in direct form
    - OK: "We have implemented a simple predictor that takes N inputs"
    - KO: "A simple predictor that takes N inputs has been implemented"

- write in a simple way
- do not use fancy words because you want your text to be "cooler"
- do not write for your advisor
- write uniformly
- it is perfectly OK to use repetitions (forget about what your high-school teacher told you)
- avoid synonyms: they confuse the reader

### Procedure

1. Have your outline ready at least 1.5 month before the submission deadline.
2. Have the bold points of the introduction ready 1 month before the submission deadline.
3. Send the outline to your advisor and wait for feedback.
4. Prepare a list of experiments (at least 3): each experiment should answer one good question to demonstrate that your approach works.
5. Have the first draft of the thesis ready 2 weeks before the submission deadline. Send it to your advisor for early feedback.
6. Have the final thesis ready 1 week before the submission deadline.
7. Pass your final thesis through a spell checker and through the [The Chrisper](https://github.com/invernizzi/chrisper).
8. Send the thesis to your advisor and wait for comments.
9. Ping your advisor if you don't receive an answer in 5 days.
10. Incorporate your advisor's comments and send your thesis to print.

### Outline

1. Introduction
    1. [contextualize the domain]
    2. [explain and motivate what is the problem with concrete numbers and objective evidence (summary of and hooks to Section 2)]
    3. [1 phrase to describe the top 1-2 state-of-the-art approaches that solve the problem (summary of and hooks to Section 2b)]
    4. [explain the top 1-2 reasons why the above 1-2 approaches fall short (hooks to Section 2b)]
    5. [explain in brief what is your proposed approach (summary of and hooks to Section 3)]
    6. [explain in brief what how/if the approach is implemented (summary of and hooks to Section 4)]
    7. [explain what results were obtained in the experimental validation (summary of and hooks to Section 5)]
    8. [conclude with a bullet list that summarizes what are the 3-4 contributions of the thesis over the state of the art]

2. Motivation
    1. Problem Statement
        1. [explain in clear terms what is the problem that you want to solve and why it is important]

    2. State of the art
        1. [divide by research direction if possible, prioritize by "strenght" and "up-to-date-ness"]

    3. Goals and Challenges
        1. [explain what problems you want to solve, and what shortcomings of state-of-the-art works you want to overcome]
        2. [explain why solving these problem (i.e., doing what you did) is challenging]

3. Approach
    1. Approach Overview
        1. [explain with simple words (max 1 paragraph) the approach to the proposed problems stated in Section 2]
        2. [divide the approach in logical steps if possible (e.g., Step 1, Step 2, Step 3)]
        3. [describe the overall approach with one or two diagrams of each step, I/O relationships should be clear to anyone, even non domain experts]

    2. Approach Details
        1. [explain the details of the approach by expanding each of the steps]

4. Implementation Details
    1. System Architecture
        1. [explain how you mapped the approach in a concrete software "product" or POC]
        2. [describe the architecture with one or two diagrams - if possible, use names that hook to the approach diagrams]

    2. System Details
        1. [for each of the implemented components that are complex enough, explain how you implemented them (i.e., what library you used, what algorithms you implemented or optimized)]

5. Experimental Validation
    1. Goals
        1. [fix and explain 1-3 goals of your experimental evaluation (i.e., what you want to show)]
        2. [if there are concrete difficulties in testing something (i.e., missing ground truth), this is a good place to explain them]

    2. Dataset
        1. [describe carefully how your dataset is structured, how you obtained it, some statistics, how big it is, how is stored]

    3. Experimental Setup
        1. [explain the details of your experimental settings (i.e., number and hardware/software characteristics of each machine)]
        2. [other people should be able to reproduce the same settings, so, be detailed]

    4. Experiment 1
        1. [explanation of the outcome - numbers are not enough]

    5. Experiment ..
        1. [explanation of the outcome - numbers are not enough]

    6. Experiment N
        1. [explanation of the outcome - numbers are not enough]

6. Limitations
    1. [explain 1-3 limitations to your approach or the implementation]
    2. [each limitation should be something that you cannot concretely have done for some reason, not something that you didn't want to do]
    3. [provide one hint on how future researchers could overcome each limitation]

7. Future Works
    1. [first, state that you will deal with the limitations]
    2. [honestly say if there is any planned work: give directions to other researches]

8. Conclusions
    1. [reprise of the goals stated in the Introduction]
    2. [aposteriori summary of what you have done]
    3. [aposteriori summary of the results]
    4. [wrapup the limitations and future works]
    5. [give your vision on the future]
