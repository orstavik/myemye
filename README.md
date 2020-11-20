# mymy
A purer Myers diff in javascript. 

## Why mymy?

1. Cleaner result by removing 'match-in-the-middle` problems. 'match-in-the-middle` problems are small text fragments (ie. individual characters or words) that needlessly breaking up an otherwise clear replacement.

2. Pure functions philosophy. Will make the code easier to understand, make efficient, improve, enhance, and debug.
 
3. Reversable output. You can use the output to go from a new version to an old version, and vice versa, simply.

4. Copy and move actions in addition to delete and insert. By adding such actions it is easier to identify many editing actions, and as a bonus, the output result is already halfway compressed.

## HowTo: use it?

```javascript
import {myersDiff} from 'https://cdn.jsdelivr.net/gh/orstavik/mymy/src/myerLifting.js';
import {myersDiff} from "../src/myerLifting2.js";
import {makeDictDiff, inverseDiff, convert, compress, extract} from "https://cdn.jsdelivr.net/gh/orstavik/mymy/src/myerDict.js";

```
``
