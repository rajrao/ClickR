#  ClickR

### A SignalR Demo where you click incessantly

+ Incorporates the standard [Chat Demo](https://www.asp.net/signalr/overview/getting-started/tutorial-getting-started-with-signalr-and-mvc "Chat Demo") by Tim Teebken and Patrick Fletchert.
    This page's side menu has other in-depth subjects that will help evolve your SignalR application.

+ A **good** :+1: reference for a game hub in the Pluralsite course
    [Building a Game of Memory with SignalR](https://app.pluralsight.com/library/courses/building-memory-game-signalr/table-of-contents "Pluralsite") by Joel Neubeck.

    > I felt that his course focused a **lot** on the game mechanics versus SignalR.
    > I don't know what the ratio is, but if he chose a simpler game (like this one) then his course would have been shorter
    > and people could have focused more on wiring up SignalR versus coding up the game mechanics.
    > Don't get me wrong, the course is **very** complete and you will have a memory game by the time you finish.
    > There was one part where he explains (in detail) about how to write an extension method.  **That's** where I started to get nit-picky. :unamused:

+ An **extremely** simple game that involves the players clicking a button.  The **more** you click, the **more** you **WIN** (as long as someone else isn't clicking more than **YOU**).

+ There is **NO** actual state management, so you are at the mercy of your hosting environment as to when your "game" may get cleared out of memory.

+ The comments in the code elaborate on decisions you may want to make for performance, etc.