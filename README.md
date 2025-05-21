# CS5800-Assignment-6-solution

Download Here: [CS5800: Assignment 6 solution](https://jarviscodinghub.com/assignment/cs5800-assignment-6-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (20 points)
The Federated States of Micronesia is a group of 607 islands in the South Pacific. These islands are
connected to each other by bridges. It may or may not be possible to move from any island to any other
island. Due to the recent machinations of North Korea, the President of Micronesia wants to perform an
assessment of accessibility in case their bridge infrastructure is bombed.
Specifically she wants to find out which bridges are critical. A bridge is critical if destroying it will
further disconnect the islands. Provide an algorithm that outputs a list of such bridges, such that any
bridge, by itself, is critical. Analyze the efficiency of your algorithm in time, clearly stating any assumptions
you make.
2. (10 points)
As the States above are made of islands, the infrastructure is distributed among islands. For example,
some islands generate electric power, others have international ports, etc. This infrastructure is routed to
other islands using communication tied to the same bridges. Perform the same assessment above, but this
time to identify which islands, if destroyed by bombing, will further disconnect the islands. Analyze the
efficiency of your algorithm in time, clearly stating any assumptions you make. Make sure your answer is
self-complete (i.e. do not assume that the reader will have read your above answer).
3. (10 points)
A saturated hydrocarbon is a molecule formed from k carbon atoms and l hydrogen atoms by adding
bonds between atoms. The bonds are such that each carbon atoms is in four bonds, and each hydrogen
1
atom is in one bond. If no sequence of bonds forms a cycle of atoms, provide an algorithm that calculates
the number of carbon atoms in a molecule, given the number of hydrogen atoms.
4. (20 points)
Its tax time! The US tax system is exceedingly complex, and you have been hired by a startup company
TaxNow! that wishes to disrupt the tax preparation software market by offering a new product. In contrast
to most tax preparation software that charge up front based on the features, TaxNow! plans to charge a
single upfront fee, and then dynamically upgrade/downgrade based on usage of actual features.
Like conventional software, TaxNow! software is built like a questionnaire: the software asks the user
about various sources of income, tax deductions, credits, etc. instead of running through the tax forms
line-by-line. It breaks the whole process down to a reasonably large set of sub-processes. Each sub-process
is a sequence of 1 or more steps that may be a question for the user, or the computation of a term. The
result of each sub-process is a certain term that is relevant to the tax system (e.g. a sub-process is about
Child Tax Credit, another sub-process is about Gambling earnings, etc.). Although each question-subset is
a fixed sequence, the subset itself may depend on other subsets: for example the total itemized deductions
cannot be computed unless the user has been asked about mortgage, property taxes, etc.
Devise an algorithm that orders the sub-processes in a way that respects the dependencies, or report
that such an ordering is not possible. Your answer must include a statement of the technical problem, any
organization of the data and the algorithm itself. You do not need to analyze its efficiency.
5. (20 points)
It would be more user-friendly if the user is asked all the questions about income together, all the
questions about tax deductions together, etc. Modify your answer to the above question so that your
algorithm now returns a correct, grouped ordering of sub-processes, or a correct but ungrouped ordering
of sub-processes, or reports that neither is possible.
