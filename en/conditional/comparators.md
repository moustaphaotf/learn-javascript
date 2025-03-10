---
chapter: 5
pageNumber: 34
description: Comparators are functions that are used to compare two values and determine their relationship. Here. the returned value indicates whether the values are equal, greater than, less than, or some other relationship based on a specific comparison criterion.  
---
# Comparators

Lets now focus on the conditional part:

```javascript
if (country === "France") {
    ...
}
```

The conditional part is the variable `country` followed by the three equal signs (`===`). Three equal signs tests if the variable `country` has both the correct value (`France`) and also the correct type (`String`). You can test conditions with double equal signs, too, however a conditional such as `if (x == 5)` would then return true for both `var x = 5;` and `var x = "5";`. Depending on what your program is doing, this could make quite a difference. It is highly recommended as a best practice that you always compare equality with three equal signs (`===` and `!==`) instead of two (`==` and `!=`).

Other conditional tests:

* `x > a`: is x bigger than a?
* `x < a`: is x less than a?
* `x <= a`: is x less than or equal to a?
* `x >=a`: is x greater than or equal to a?
* `x != a`: is x not a?
* `x`: does x exist?

## Logical Comparison

In order to avoid the if-else hassle, simple logical comparisons can be utilised.

```javascript
let topper = marks > 85 ? "YES" : "NO";
```

In the above example, `?` is a logical operator. The code says that if the value of marks is greater than 85 i.e. `marks > 85` , then `topper = YES` ; otherwise `topper = NO` . Basically, if the comparison condition proves true, the first argument is accessed and if the comparison condition is false, the second argument is accessed.
