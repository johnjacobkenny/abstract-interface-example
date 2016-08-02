# abstract-interface-example

## animal.abstractclass
This package contains an abstract class `Animal` and its concrete implementations `Dog` and `Cat`. An abstract class would be the correct way to go in this scenario, since many elements are common and reuseable.

## animal.intrface
This package contains an interface `Animal` and two classes `Dog` and `Cat` which implement it. In this example the interface forces the developer to provide separate implementations for the same functionality. (_intrface_ is not a typo, java won't allow package names to use java keywords)

## person
This package shows how to use interfaces effectively. It has three unrelated classes like `Person`, `Dog` and `Monkey` which are grouped together using the interface `Singable`. The `Singable` interface specifies that anyone who implements it will know how to `sing()`. `SingingDancingMonkey` shows how to implement multiple interfaces.
