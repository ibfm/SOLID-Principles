# SOLID Principles

### What is SOLID?
SOLID is an acronym for the most popular design principles for object-oriented software development.
The acronym was created by Michael Feathers after noting that five principles of object orientation and code design — created by Robert C. Martin (a.k.a. Uncle Bob) and covered in The Principles of OOD — could fit this word.

### S.O.L.I.D: The 5 Principles of OOP
#### S — Single Responsibility Principle
##### | A class should have only one responsibility hence only a single purpose |
##### | Benefits: Understandable, Maintenable and Less Frequently Changed
#### O — Open-Closed Principle
#### L — Liskov Substitution Principle
#### I — Interface Segregation Principle
#### D — Dependency Inversion Principle

These principles help the programmer to write cleaner code, separating responsibilities, reducing coupling, facilitating refactoring and encouraging code reuse.

### Robert Martin commandments

1. Software entities (classes, modules, etc) should be open for
extension, but closed for modification. (The open/closed
principle -- Bertrand Meyer)

2. Derived classes must usable through the base class interface
without the need for the user to know the difference. (The
Liskov Substitution Principle)

3. Details should depend upon abstractions. Abstractions should
not depend upon details. (Principle of Dependency Inversion)

4. The granule of reuse is the same as the granule of release.
Only components that are released through a tracking system can
be effectively reused.

5. Classes within a released component should share common closure.
That is, if one needs to be changed, they all are likely to need
to be changed. What affects one, affects all.

6. Classes within a released componen should be reused together.
That is, it is impossible to separate the components from each
other in order to reuse less than the total.

7. The dependency structure for released components must be a DAG.
There can be no cycles.

8. Dependencies between released components must run in the
direction of stability. The dependee must be more stable than
the depender.

9. The more stable a released component is, the more it must
consist of abstract classes. A completely stable component
should consist of nothing but abstract classes.

10. Where possible, use proven patterns to solve design problems.

11. When crossing between two different paradigms, build an
interface layer that separates the two. Don't pollute one side
with the paradigm of the other.
