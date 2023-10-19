# Looping a triangle

Write a loop that makes seven calls to console.log to output the following triangle:

```js
#
##
###
####
#####
######
#######
```



let x = "#";
console.log(x);
let z = 0;
while (z <= 7) {
    console.log(x+x)
    z =+1 ;
}


It may be useful to know that you can find the length of a string by writing .length after it.

```js
let abc = "abc";
console.log(abc.length);
// → 3
```
