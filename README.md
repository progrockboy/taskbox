# taskbox

>I'm Nick. Mostly I record music and create educational theatre with my wife, but I have an interest in programming that won't leave me alone, and since I now have a decent enough idea to focus on, I've decided to give it a good honest shot.
>My kids are very list driven. I'm trying to save paper. Desired end result: a program that will accept an arbitrary number of tasks, take that list, generate an array of labeled buttons with boolean clicked states for each item, and then display and update them. Once all tasks are mouse clicked=true, perform a cute animation and ask to reset.

## pseu pseu pseudocode

1. **UI**
    1. rectangular tiles for entered tasks
        1. tap to complete
        1. *completing all tasks does super cool animation*
    1. entry page for tasks
        1. Task name
        1. who's it for?
        1. *what's the benefit?*
1. **Tiles**
    1. simple array
        1. color change on tap
    1. animated shutdown for completion
    1. display task text
1. **Interaction**
    1. pop up floating text reinforcing benefit text on complete 
