# RevolutionCASE
This project is a resulting product of my master's degree research.
 The RevolutionCASE Tool enables the developer to automatically and visually execute structural refactor on a production database. 
 RevolutionCASE has the following features: 
 - Partial Reverse Engineering: the developer brings to the canvas only the concerning tables to refactor 
 - Modeling Language: using a unique language to model both relational and refactoring, the RevolutionCASE tool delivers simple constructors and properties to set up and run the refactoring quickly 
- Script Generation or Forward Engineering: It's up to the developer whether he wants to run the refactoring straight from the tool or copy the script from the Script View
- It worth note that all refactorings, as well as the research that inspired this tool, was based on Pramod Sadalage's book Refactoring Databases : Evolutionary Database Design

## Caveats:
- For now, only the PostgreSQL database is supported
- We performed experiments using copies of real databases, but we strongly recommend that you set up a sandbox environment in order to validate the results. We also reinforce
that we did not stress all industrial use cases. So use it carefully.

Any suggestions or comments please, let me know. You can hit me on:
email: profgenesislima@gmail.com or gjfpl@cin.ufpe.br
phone: +5581971085512

## Team
- Gênesis Lima (Researcher and Developer)
- Robson Fidalgo (Supervisor and Q&A)
- Edson Alves (Consultant and Q&A)
