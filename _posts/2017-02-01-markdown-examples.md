---
title:  "Markdown examples"
layout: post
---

aaaa

## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)


## Blockquotes

### Single line

> b
### Multiline

> c
> d

## Horizontal Rule

---

## Table

| Title 1          | Title 2          | Title 3         | Title 4         |
|------------------|------------------|-----------------|-----------------|
| First entry      | Second entry     | Third entry     | Fourth entry    |
| Fifth entry      | Sixth entry      | Seventh entry   | Eight entry     |
| Ninth entry      | Tenth entry      | Eleventh entry  | Twelfth entry   |
| Thirteenth entry | Fourteenth entry | Fifteenth entry | Sixteenth entry |

## Code

Source code can be included by fencing the code with three backticks. Syntax highlighting works automatically when specifying the language after the backticks.

````
```javascript
function foo () {
    return "bar";
}
```
````

This would be rendered as:

```javascript
function foo () {
    return "bar";
}
```

## Lists

### Unordered

* First item
* Second item
* Third item
    * First nested item
    * Second nested item

### Ordered

1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
