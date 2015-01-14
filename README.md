---
tags: recursion, todo, ruby, kids
languages: Ruby
resources: 2
level: intermediate
---

## Mine Sweeper

### Background

Danny accidentally placed mines around the campus.  What can we say? Mistakes were made. Luckily he mapped out the spots where he placed them in a two dimensional array.

Danny's Map
```ruby
[
  [0,  0,   0,  0, '*'],
  [0,  0,  '*', 0,  0 ],
  [0,  0,   0,  0,  0 ],
  [0, '*', '*', 0,  0 ],
  [0,  0,   0,  0, '*']
]
```
### Instructions

Before we can begin defusing the mines we need to figure out the most dangerous spots by counting how many mines each tile touches.This is going to mean moving through each row on the map until you find a mine and then incrementing all the surrounding tiles by one. (Take a look at the spec to get a sense of what your solved mine map should look like.) Keep in mind (or should we say "mine"???) that this is going to need to happen one row at a time, and a row isn't finished until every affected tile is incremented.

## Bonus
Solve this using recursion.

## Resources
* [Odin Project](http://www.theodinproject.com/) - [Recursion](http://www.theodinproject.com/ruby-programming/recursive-methods)
* [Joshua Creek's Ruby Kickstart](http://vimeo.com/user3374111/videos) - [Introduction to Recursion](http://vimeo.com/24716767)