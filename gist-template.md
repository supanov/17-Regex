# Regex - Matching an Email 

This tutorial will provide an explanation of the components of regex for matching an email. 

Regex or regular expression is a sequence of characters that defines a specific search pattern used to identify an email address. This is useful in technologies such as Node or MongoDB


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Greedy and Lazy Match](#greedy-lazy-match)

## Regex Components
This is the regex component:  /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
Anchors are used to indicate the beginning of the sting and ending the of the string. 

 ^ - this anchor is the beginning of an empty string
 $ - this anchor signals an end to a string

### Quantifiers
Quantifiers, group or connect the user + email + .com. 

{2,6}, is a range that of 2-6 characters from the character set [a-z\.]

### Bracket Expressions
Bracket expression is used to match letter sets through a-z and is also case sensitive. It also matches the character-digit 0-9, and also literal dot and hyphen. 

‹[A-Z0-9.-]› and other sequences between brackets are character classes

### Character Classes
\d is the character class.

 It matches single character-digits from 0-9. It only matches single digits not double digits. 

### Greedy and Lazy Match 
Greedy: i.e. '+)@('
Lazy: ? , * , {}

Regex's purpose is to return a match, which will report the first possible match. Since this regular expression includes + quantifieer, it will match as few times as needed. 


## Author

This gist was created by Novia on @supanov GitHub profile. https://gist.github.com/supanov
