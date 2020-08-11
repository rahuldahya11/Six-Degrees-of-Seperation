# Six Degrees of Kevin Bacon

## Contex
Six degrees of separation is the idea that all people on Earth are six, or fewer, social connections away from each other. Also known as the 6 Handshakes rule. As a result, a chain of "a friend of a friend" statements can be made to connect any two people in a maximum of six steps.

## About this Project
Six Degrees of Kevin Bacon or "Bacon's Law" is a parlor game based on "six degrees of sepearation" concept, which posits that any two people on Earth are six or fewer acquaintance links apart. Bacon's Law rests on the assumption that anyone involved in the Hollywood film industry can be linked through their film roles to Bacon within six steps. The challenge is to find the sortest path between any two arbitrary actors/actresses using the breadth-first search method.

## Data
The data is from an IMDB database that contains three different data sets. The first dataset(movies.csv) being the move name along with its movie identification number. The second dataset (people.csv) contains the actors/actresses name along with their identification number. The third dataset (stars.csv) establishes a relationship between the people and the movies.

## Testing
Clone this repository to your local machine and run the following argument in the terminal `python degrees.py small`.
The data files within "Data/small" contain a fraction of the data that is in "Data/large" for ease of testing and experimentation.

## How to Use
Clone this repository to your local maching and run the following argument `python degrees.py large`.
Enter the names of two actors/actresses when prompted and then an output displaying the number of degrees and a description of their paths will appear. It is possible there could be multiple minimum paths between the same two people so the output could display a different path but with the same number of degrees.
