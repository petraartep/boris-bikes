# User stories

## User stories
```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike is working
```

## Nouns
- person
- bike
- docking station

## Verbs
- use
- release a bike
- see if a bike is working

---

Objects | Messages
--------| --------
User
Bike | working?
DockingStation | release_bike


## Diagram 
```
Bike - working? --> true/false
DockingStation - release_bike --> bike
```