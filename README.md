# Matching an Email using Regular Expressions #

Regular Expressions, or regex, are sequences of characters that form a search pattern. These can be helpful in coding, as they are used to confirm the presence of a specific pattern in a string, using letters, numbers, and special characters.
This information can then be extracted from the text for various purposes. Some examples of regex include patterns for matching usernames, URL's, HEX values, and, for this tutorial's example, email addresses.

## Summary

In this gist, we will be examining the regex code for verifying that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each part of this expression gives specific instructions for what to find or validate on a webpage. The next sections will break down this code to help understand what it means and how it works.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

the / symbols mark the beginning and end of the regex pattern
unspecified number of characters, including digits 0-9, upper or lower case letters a-z
\d can be used in place of any digit from 0 to 9


### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

### Resources Used

- YouTube: The Coding Train
- W3Schools
- regexone.com
- codeburst.io

## Author

My name is Sean Gordon. I'm a software development bootcamp student through Rutgers University. I'm excited to continue learning and enter the field. Please visit my [Github page](https://github.com/nodrognaes) or email any questions to [nodrog.naes@gmail.com](mailto:nodrog.naes@gmail.com).
