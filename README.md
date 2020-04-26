# Canonical Names

This is a collection of the canonical names\* of Science Olympiad schools\*\* and
events, which are used to track those teams and events across tournaments.

In many cases, there is often more than one way to represent the name of a
school or event, making it difficult to simply search for all the results for a
particular one. This collection attempts to fix this problem by picking one name
as "canonical" for each school and event, and requesting that all mentions of
such in Science Olympiad results use that name.

\*Nothing to do with CNAME records in spite of the name.

\*\*This includes organizations like the Central Texas Science Team, which
compete in Science Olympiad tournaments but are not schools in the traditional
sense.

## Format

The collection consists solely of two files, `schools.csv` and `events.csv`, in
which school and event names are listed in alphabetical order, one entry per
line.

### Schools

Each entry in `schools.csv` consists of three sections separated by commas:
school name, city, and state code. For example here are three schools:
```
Adlai E. Stevenson High School,,IL
Athens High School,Troy,MI
"Gwinnett School of Mathematics, Science, and Technology",,GA
```
Note the following rules apply:
- city name is optional if the name of the school is unique to the state
- double-quotes surround the school or city name if the name itself has commas
- states are represented by their two letter state abbreviation

### Events

Each entry in `events.csv` is simply the name of the event. For example:
```
Anatomy and Physiology
Astronomy
Boomilever
```
