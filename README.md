# Interesting Software Engineering Article -- Ishana Goyal

## [Software Engineering Fundamentals for Data Scientists](https://towardsdatascience.com/software-engineering-fundamentals-for-data-scientists-6c95316d6cc4)

I found this article particularly interesting because this summer I worked a data analyst for an equities fund. However, I noticed a lot of inefficiencies in the code I was writing day-to-day, and this article summarized a ton of different ways to improve my code by incorporating software engineering fundamentals. 

Here is a brief summary of my takeaways:
- Modular code is super important -- this means building classes with attributes and methods so that it easier to productionize my code and reuse modules in other programs. 
- Refactoring is the process of re-designing one's code without changing the output. This is key to improving my code's readability and creating an easy-to-review internal architecture. 
- Part of refactoring includes using vectorized operations and using NumPy instead of Pandas when possible (this was particularly shocking since everyone on the team this summer used Pandas religiously).
- Always test and review your code!

Hopefully I can apply some of these software engineering fundamentals (and more that I learn throughout the semester) to my data science functions!


- Shannon Huang's Comment: I also found this article super helpful! It's interesting  that a lot of these ideas seem pretty intuitive--such as writing clean code--but at the same time, they show that there's a clear difference in simply getting software built and getting it built in an efficient and systematic way.