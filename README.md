# PHIL 201 Final Study Guide

## Contents
* Sentential Logic
    * Definitions
    * Translations
    * Truth Tables
    * Truth Trees
* Predicate Logic
    * Definitions
    * Translations
    * Truth Trees

## Sentential Logic

### Definitions

### Translations
You are given a sentence in English and asked to translate to Sentential Logic

if given the following relationships, answer 1-3:
```
A. He will go fishing.
B. He will buy soda.
C. It will rain. 
```

1. He won't go fishing whether he buys soda or not.
```
~A & (B v ~B)
explanation: He won't go fishing (~A) whether (&) he buys soda (B) or (v) not (~B).
```
2. He will go fishing and buy soda, unless it rains.
```
(A & B) v C
explanation: go fishing (A) and (&) buy soda (B), unless (v) it rains (C)
```
3. He will go fishing even though he will buy soda.
```
A & B
explanation: go fishing (A) even though (&) buy soda (B)
```

### Truth Tables

| A  | B  |A & B|A v B|A ⊃ B|
|:--:|:--:|:--: |:--: |:--: |
| T  | T  | T   | T   | T   |
| T  | F  | F   | T   | F   |
| F  | T  | F   | T   | T   |
| F  | F  | F   | F   | T   |


### Truth Trees

## Predicate Logic

### Definitions

### Translations

### Truth Trees