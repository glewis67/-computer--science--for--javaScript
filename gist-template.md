# Title (Validate an Email Address)

Introductory paragraph 
A brief summarization of validaing and email address explaining each functionalty of each
regex components and how it applies matching the correct email address inputed by the user then validated by regular expressions.

## Summary

To validate an email address by its regualr expression that is a sequence of a character which define the specific pattern and also named as abbreviated regex or regexp and sometimes called a rational expression. 

/^w+[+.w-]*@([w-]+.)*w+[w-]*.([a-z]{2,4}|d+)$/i

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
 They do not match any character at all. Instead, they match a position before, after, or between characters. They can be used to “anchor” the regex match at a certain position.
### Quantifiers
It matches and validate with regular expressions that are sequences of metacharacters, denoting a pattern. There are a various kind patterns it can be of: a mix of letters with digits, special characters and even different language characters. An abbreviation for regular expression is RegEx or RegExp.

### OR Operator
The operator | can be use as a alternation in regular expression that is actually a simple “OR”. It be can use to match characters or expression of either the left or right of the | operator. For example the (p|P) will match either p or P from the input string.
 
### Character Classes
Character class also called character set the user can tell the regex engine to match only one out of several characters. For example input the characters that you want to match between square brackets [ar]. This could be used in b[ar]e to match either bare or bear. 

### Flags
A flag variable, it looks for the one true value that is define to one value where the condtion is true. It is a variable that the user can control the flow of a function or statement, allowing the user to check for certain conditions while your function progresses.
### Grouping and Capturing
 Using part of a regular expression inside round brackets{} or parentheses(). The regular expression can be group together by the user. This allows a quantifier to be applied to the entire group or to restrict alternation to be part of the regex.
### Bracket Expressions
 A list of characters [+.w-] enclpsed in a bracket. Any single character is match in that list. If the first character of the list is a caret ‘^’, "then it matches any character not in the list, and it is unspecified whether it matches an encoding error. For example, the regular expression ‘[0123456789]’ matches any single digit, whereas ‘[^()]’ matches any single character that is not an opening or closing parenthesis, and might or might not match an encoding error."For example, [def] matches d, e, or f, but not a, b, or c.
### Greedy and Lazy Match
 All quantifier are greedy always attempting to repeat the sub-pattern as many times as possible before exploring shorter matches by backtracking.

A lazy quantifier pattern will always take the shortest possible string to match and repeat the sub-pattern few times as posssible before expanding a longer match pattern. To make it lazy just append the existing quantifier.
### Boundaries
Like the caret and the dollar sign  $ the metacharacter \b is also an anchor. The position it matches is called a “word boundary”. Zero-length is this match.
"\b allows you to perform a “whole words only” search using a regular expression in the form of \bword\b. A “word character” is a character that can be used to form words. All characters that are not “word characters” are “non-word characters”."
### Back-references
"It is used to match the same text previously matched by a capturing group. This both helps in reusing previous parts of your pattern and in ensuring two pieces of a string match."

"If the user is are trying to verify that a string has a digit from one to nine, a separator, such as hyphens, slashes, or even spaces, a uppercase letter, lowercase letter,another separator, then another digit from one to nine can be used.
#Lookahead and lookbehind, collectively called “lookaround”, are zero-length assertions just like the start and end of line, and start and end of word anchors explained earlier in this tutorial. The difference is that lookaround actually matches characters, but then gives up the match, returning only the result: match or no match. That is why they are called “assertions”. They do not consume characters in the string, but only assert whether a match is possible or not. Lookaround allows you to create regular expressions that are impossible to create without them, or that would get very longwinded without them.## Look-ahead and Look-behind"

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
