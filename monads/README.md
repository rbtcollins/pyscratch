exploring using generators as part of / a consistent monad interface

Data dependencies in Python:
 - goal: ordered code runs in order
 - its imperative code, nothing to do

Maybe and Either in Python:
 - context represents computation success/failure
 - values are == Just/Right
 - exceptions are Nothing/Left
 - pattern matching on Nothing/Left is try/except.
 - tl;dr nothing to do in Python

List in Python:
 - Want it to be lazy: no need to compute more than consumed
 - <*> is the key operator
 - 
