# Learning Goals and Success Criteria

## Understand why source control is important in software development:

- I can describe the process by which multiple people can work on the same project (files) without destructive changes.
- I can name major organizations that depend on Git to manage their products.
- I can name several alternatives to Git and explain why Git is dominating the market.
- I can describe situations where the revision history of a file can be used to find the origin of a bug/problem.

## Realize that source control tools can and are being used for purposes beyond software:

- I can show several public projects on GitHub or Gitlab that are not related to software; ie. books, tutorials, etc.
- I can list the types of files that are ideal for source control and types that are not.

## Know how to use Git:

- I will work with my peers to update the same document in a shared Git repository.
- I will create a project on cloud services: GitHub or Gitlab.
- I can clone a Git repository onto my local computer. (if permitted)
- I can commit my changes to a file along with an accurate comment about the changes.
- I can push my changes to a remote branch.

# Materials and Resources

- [Lesson slide show](https://docs.google.com/presentation/d/1PPPLqO337iggQbUxZfYzsG-zL5U4L1N9mWZDLDOPej0/edit?usp=sharing)
- [Git introduction and reference](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
- [Git tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
- [Git online interactive tutorial](https://www.katacoda.com/courses/git)
- [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub statistics and infographics](https://octoverse.github.com/)
- [Open Source resources](https://opensource.com/resources/what-open-source)

# Instructional Sequence

## Minds On - 50 min

Take oral survey on experience with Git or other source control tools - 5 min
“Do you know what source control or version control systems are?”
“Have you ever used source control?”
“Have you ever used Git?”
“Do you have an account on GitHub or Gitlab?”

Discuss the purpose of source control and merits of Git using the Horse-drawing exercise analogy - 20 min
“What happens if you have a program you’ve been working on for weeks on your local computer and something happens to that computer: stolen, hardware malfunction, ransomware, etc.?
Start over,
Try to recover, but what are the costs?
“Let’s say you’ve been revising your program over several months to make it better and suddenly you realize that there is a terrible bug that was introduced as part of a feature you implemented a while ago; how do you figure out where that bug is if you have no history of all your changes?”
Start tracing from the beginning of the program; but imaging a program with millions of lines of code.
Trial and error; but there are likely a huge number of scenarios to cover.
“What do we need to avoid those problems?”
Revision history: who, what, when
Backups of all variations (branches)
Explain the term “branching”
“What tools are available for source control?”
CVS, SourceSafe, Subversion, Git, etc.
“Why Git?”
Branching is cheap
Open source, well maintained.
It has won; ie. most corporations and institutions prefer it.
Incredible amount of support and tooling around it: GitHub, Gitlab, Bitbucket, etc.
(show GitHub statistics)
Discuss key concepts: 25 min
Clone, branch, commit, push, pull, fork
“What is the difference between branching and forking?
Forking is usually intended to be more permanently divergent
Branching is intended to temporarily divergent, then converge

## Action

Katacoda Git tutorial - 20 min
https://www.katacoda.com/courses/git

Getting started with GitHub - 25 min
Create GitHub accounts.
Explore GitHub.

In Groups of 2 or 3 co-create a story (single file) using GitHub and Markdown - 35 min
Group discussion on the story and delegation of responsibilities.
Research Markdown as a file format and syntax.
“Why use Markdown?”
Non-proprietary format; widely adopted; efficient.
Create one project per group on either GitHub.
Each member clone the repository and work on their parts or use GitHub’s GUI directly.
Use Git commits and merge requests to combine the parts.

## Consolidation and Connection

Discussion on Git experience - 30 min
“What challenges did you encounter and how did you overcome them?”
“Do you know how indirectly dependent you are on Git?”
Linux and open source software touches all of us… eg. your phone wouldn’t work without them.
(show more Git statistics)
“What is Open Source?”
(point to resources about Open Source)
“How important will Git and source control in general be in a Computer Technology career?”
Like a “saw” is to a carpenter.
Like “order” from “chaos”.
Even if you don’t do software development, the idea of revision control is vital in many contexts.
