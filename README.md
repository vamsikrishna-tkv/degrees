# degrees
This is a program that determines how many “degrees of separation” apart two actors are.

Explation:According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.
In this problem, we’re interested in finding the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”


``` CMD To Run the programe ```
python degrees.py large

#here large is the main file and there is an another set of files named small used for testing (By default it takes the large data set).

``` END of CMD ```

ALGORITHM used for traversing BFS(Breadth First Search).
