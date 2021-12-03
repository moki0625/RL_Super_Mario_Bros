# RL_Super_Mario_Bros
Study materials and code for implementation reinforcement learning on Super Mario Bros


NOTE OF GYM LIBRARY

- Gym Wrappers
Wrappers will allow us to add functionality to enviornments, such as modifying observations and rewards to be fed to our agent.
Common in RL to preprocess observations in order to make them more easy to learn from.

Implementing the gym.Wrapper class requires defining an __init__ method that acccepts the environment tobe extended as a parameter.


-----------------------------------------------
UNDERSTANDING SELF AND __INIT__ METHOD IN PYTHON

-Class: A set of category of things having
some property or attribute in common and 
differentiated from others by kind, type or
quality.
-Object: One of intances of the class which can
perform the funcionalities which are defined in
class.
-Self: Represents the instance of the class. By
using the 'self' keyword we can access the
attributes and methods of the class in python.
-__init__: is a reserved method in python classes.
It is known as a constructor in object oriented
concepts. This method called when an object is
created from the class and it allow the class
to initialize the atrributes of a class.
-----------------------------------------------

1) gym.ObservationWrapper: Used to modify the observations returned by the enviroment.
2) gym.RewardWrapper: Used to modify the rewards returned by the enviorment.
3) gym.ActionWrapper: Used to modify the actions passed to enviorment.

**super()**
A common use for this function is building classes that extend the functionality of previously built calsses.
Calling the previously built methods with super() saves you from nedding to rewrite those methods in your subclass, and allows you to swap out superclasses with minimal code changes.

