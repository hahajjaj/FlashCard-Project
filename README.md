# English Version
# Flashcard
## Project Description
First of all, this project has been imported from the private school's GitLab server, and it currently has no commit history.
For this project, we developed a flashcard application that is executable on Linux, Windows, and MacOS. To accomplish this, we employed the JAVA programming language.
This project was undertaken using the XP agile methodology. Our main objective was to create a comprehensive flashcards application with the following features,
1. A secure login system.
2. A fully implemented card package management.
3. Diversity of card types such as multiple choice, open response and blank text to complete.
4. A system to import and export a card package in your computer.
5. A store where you can download other players custom card packages and upload yours as well.
6. Storage and data management in a database.
7. Multiple Learning Modes: Our application supports various learning modes to cater to different learning styles and needs. These modes include:
                          -Normal Revision: Users can review their flashcards at their own pace.
                          -Quiz Mode: Users can test their knowledge with randomized questions.
                          -Custom Difficulty Mode : Users can choose a difficulty mode for a certain card package from level 1(easiest) to 3(hardest).
8. Implementation of a server using sockets to enable communication among users.
9. Progress Tracking: The application keeps track of users' progress and performance.
10. Personal score and a ranking system.
11. A Text to speech system.
12. Modular Card : The users can create math questions with variables that are going to be given random values. For example a card with the question: a+b will always have a random answer.

Throughout the project, we applied agile principles and collaborated effectively within the team. We successfully developed a robust, cross-platform application using JAVA. We also tackled various technical challenges and provided a complete solution for learning project management.

## Quick links
- [Dependencies](lib/setup.md)
- [Compilation steps](dist/compilation.md)
## Setup
> To setup project dependencies, see [this document](lib/setup.md)

Since iteration 2 and the creation of the server, the application can no longer be launched
alone: ​​you must also launch the server application for this,
1. Go to `Run -> Edit Configuration`
2. Add an application that uses `Server.java` as its main class
> It is possible to launch the server and the client in a single click by 
> adding in a compound 
## Using the jar
If you use the pre-compiled `.jar` (for Windows), enter these commands in
the terminal to launch the client and the server,
```agsl
java -jar /path/to/g9-iteration-4.jar 
java -cp /path/to/g9-iteration-4.jar ulb.infof307.g9.server.Server
```
> Please note, the application will not work correctly if the server
> is not launched. Because, since iteration 2, many actions have taken place
> by the latter
### Other OS
You must [compile](dist/compilation.md) the `.jar` yourself. You will find it in
`/target` under the name of `g9-iteration-2-shaded.jar`
> Do not make the mistake of `.jar` because the unshaded version
> **It won't work** 