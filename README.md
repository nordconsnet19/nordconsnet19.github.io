## The Workshop

The [Nordic Network for researchers and practitioners of Constraint programming (NordConsNet)](http://www.it.uu.se/research/NordConsNet) kindly invites you to participate in the yearly NordConsNet Workshop. 
The purpose of the workshop is to learn about ongoing research in Constraint Programming and optimisation, existing projects and products, and further development of the network. 
NordConsNet Workshop 2019 is the 18th edition of this annual event.

## Date

The workshop will be held on Tuesday, 21.05.2019. The workshop program will start at 10:00 (see program below), but we invite everyone to arrive earlier for a nice cup of coffee and a chat with the other participants.

## Location

The workshop will take place at _[Simula Research Laboratory](https://www.simula.no/), Martin Linges vei 25, 1364 Fornebu, Norway_. [How to get to Simula](https://www.simula.no/about/contact-simula).
Simula is located in the Technopolis building. 
Simula's main entrance is on the 3rd floor, turning right up the stairs from the Technopolis main reception area.

## Program

| Time          | Presenter         | Title                                                     |
| ------------- | ----------------- | -----                                                     |
| 09:30 - 10:00 |                   | Morning Coffee                                            | 
| 10:00 - 10:10 | Helge Spieker     | Welcome                                                   | 
| 10:10 - 10:30 | Arnaud Gotlieb    | Simula Research Laboratory: Constraint Programming for Software Engineering                                       | 
| 10:30 - 11:00 | Gustav Björdal    | Generating Compound Moves in Local Search by Hybridisation with Systematic Search |
| 11:00 - 11:30 |                   | Presentation (T.B.A.)                                     | 
| 11:30 - 12:00 |                   | Presentation (T.B.A.)                                     |
| 12:00 - 13:30 |                   | Lunch                                                     | 
| 13:30 - 14:00 | Matti Järvisalo   | CP at the University of Helsinki                          | 
| 14:00 - 14:30 | Nadjib Lazaar     | Constraint Acquisition                                    | 
| 14:30 - 15:00 |                   | Presentation (T.B.A.)                                     | 
| 15:00 - 15:30 |                   | Coffee Break                                              | 
| 15:30 - 16:00 | Mathieu Collet    | Stress Testing of Single-Arm Robots Through Constraint-Based Generation of Continuous Trajectories                                                   | 
| 16:00 - 16:30 | Jo Devriendt      | Leveraging LP solving for PB solving                      | 
| 16:30 - 17:00 |                   | Presentation (T.B.A.)                                     | 
| 17:00 - 17:10 |                   | Closing                                                   |
| 18:00         |                   | Dinner at Scandic Fornebu                                 | 


## Abstracts

### Simula Research Laboratory: Constraint Programming for Software Engineering.
**Arnaud Gotlieb (Simula Research Laboratory)**

Since 2001, Simula emphasizes and promote basic research for tackling scientific challenges with long-term impact and of genuine importance to real life. 
Among the carefully selected research fields investigated from its origin, Software Engineering has been a wide and fruitful area to explore with techniques coming from Artificial Intelligence, namely Constraint Programming (CP) and Machine Learning (ML). 
This talk will briefly review the various research activities held in the side of CP and will present some of the most significant Simula's innovative projects. 

### Generating Compound Moves in Local Search by Hybridisation with Systematic Search
**Gustav Björdal (Uppsala University)**

A black-box local-search backend to MiniZinc automatically infers from the structure of a declarative model a neighbourhood, heuristic, and meta-heuristic. 
These ingredients are then provided to a local-search solver. 
However, such a backend can perform poorly due to model structure that is inappropriate for local search, for example when it considers moves modifying only variables that represent auxiliary information.

Towards overcoming such inefficiency, we propose compound-move generation, an extension to local-search solvers that uses a complete-search solver in order to augment moves modifying non-auxiliary variables so that they also modify auxiliary ones.

In this presentation I will give a motivating example for this work and an overview of our approach.

### T.B.A.

### T.B.A.

### Constraint Reasoning and Optimization at University of Helsinki
**Matti Järvisalo (University of Helsinki)**

The [Constraint Reasoning and Optimization Group](https://www.helsinki.fi/en/researchgroups/constraint-reasoning-and-optimization) at the University of Helsinki, Finland, focuses on the development of Boolean satisfiability (SAT) solving techniques and SAT-based and other discrete search and optimization procedures for exactly solving intrinsically hard (NP-complete and beyond-NP) real-world problems. 
In this talk I will give an overview of some of the key contributions and main research directions of the group, with more details (as time permits) on hybrid SAT-IP approaches and applications of constraint solvers in the context of structure learning for probabilistic graphical models.


### Constraint Acquisition
**Nadjib Lazaar (LIRMM – CNRS, U. of Montpellier, France)**

Constraint programming is used to model and solve complex combinatorial problems.

The modeling task requires some expertise in constraint programming. This requirement is a bottleneck to the broader uptake of constraint technology.

Several approaches have been proposed to assist the non-expert user in the modeling task. 
In this talk, I will present the recent results on constraint acquisition obtained by the Coconut team and their collaborators. 
In a first part I will show how to learn constraint networks by asking the user partial queries. 
That is, we ask the user to classify assignments to subsets of the variables as positive or negative. 
We provide an algorithm, called QUACQ, that, given a negative example, finds a constraint of the target network in a number of queries logarithmic in the size of the example. 
In a second part, I will show how to make constraint acquisition more efficient in practice (new kind of queries, the use of some background knowledge, more elicitation…).

### T.B.A.

### Stress Testing of Single-Arm Robots Through Constraint-Based Generation of Continuous Trajectories
**Mathieu Collet (Simula Research Laboratory)**

T.B.A.

### Leveraging LP solving for PB solving
**Jo Devriendt (KTH)**

Pseudo-Boolean (PB) solvers  are algorithms for 0-1 integer linear
programming, with state-of-the-art PB algorithms mimicking the succesful
conflict-driven clause-learning (CDCL) paradigm from Boolean
satisfiability (SAT). However, although PB solver can be exponentially
stronger than CDCL solver, they can also get hopelessly stuck in
rationally infeasible parts of the search space, where it should be easy
to see that there are no solutions.

To remedy this, we integrate a linear programming (LP) solver in the PB
solver algorithm. A straightforward hybrid algorithm encounters two
problems. First, running an LP solver might starve the PB solver, as
calling an LP solver is orders of magnitudes costlier than executing an
iteration in the PB solver search loop. Second, most LP solvers use
imprecise floating-point arithmetic, which can cause problems with
soundness. We propose a hybrid PB+LP approach that addresses these
issues. We present experimental results of an implementation that show
large speed-ups on certain benchmark families and only incur moderate
overhead in general.

### T.B.A.


## Organisation

The NordConsNet Workshop 2019 is chaired by [Arnaud Gotlieb](https://www.simula.no/people/arnaud) and [Helge Spieker](https://www.simula.no/people/helge) (both [Certus SFI](http://certus-sfi.no/) & Simula Research Laboratory).


## Registration (Closed)

To register please send an email to [Helge Spieker](https://www.simula.no/people/helge).
Registration including lunch and catering must be send prior to May, 3. 
If you register after that date, you are still very welcome to attend any talks during the day, just be mindful not to enter during a talk and don't expect catering.
There are no registration fees for the workshop.

Please forward this information to anyone who might be interested in this workshop but is not yet on the NordConsNet mailing list: they can subscribe to it by applying to [Justin Pearson](http://www.it.uu.se/katalog/search.php?name=Justin%20Pearson&exact=yes).


## Submit a Presentation Proposal (Closed)

We hope for your participation, and highly encourage you to submit a proposal for a presentation of your ongoing work, recent results, or of a relevant discussion topic. 
There are no paper submissions, reviews, or proceedings, hence recent conference/journal papers may also be presented. 
Please contact [Helge Spieker](https://www.simula.no/people/helge) if you would like to present.

