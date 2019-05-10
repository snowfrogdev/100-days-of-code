# 100 Days Of Code - Log

## Day 19: May 10, Friday

**Today's Progress**: Worked on the 'Bender - Episode 1' puzzle on codingame.com. Learned about the state pattern.

**Thoughts** The State pattern seems strange to me. On the surface it seems to encourage composition, but if you have many, many States that are similar to each other, you'll probably end up using some sort of inheritance hierarchy. Also, the tight coupling between the context and the states and between the states themselves makes me uneasy.  I could be wrong, I still have to play with the pattern to fully understand it.

### Link(s) to work

1. [Bender - Episode 1](https://github.com/snowfrogdev/codingame/tree/master/bender-1)

## Day 18: May 9, Thursday

**Today's Progress**: Solved the 'Order of Succession' puzzle on codingame.com. Got to use a tree data structure and depth first search algorithm. It had been a while. Also wrote up a blog article on the left shift bitwise operator.

**Thoughts** Writing blog articles really doesn't come easy. I can't help but feel that every subject has already been thoroughly written about. Yet, it does help cement in my mind  things I have just learned.

### Link(s) to work

1. [Order of Succession](https://github.com/snowfrogdev/codingame/tree/master/order-of-succession)
2. [An introduction to the left shift bitwise operator](https://blog.snowfrog.dev/left-shift-bitwise-operator/)

## Day 17: May 8, Wednesday

**Today's Progress**: Solved the 'Bank Robbers' puzzle on codingame.com. Learned that `x * 2 ** y === x << y`.

**Thoughts** It was fun to get reaquainted with permutations and combinations equations. Some of the 'easy' puzzles on codingame.com are not all that easy.

### Link(s) to work

1. [Bank Robbers](https://github.com/snowfrogdev/codingame/tree/master/bank-robbers)

## Day 16: May 7, Tuesday

**Today's Progress**: Solved the 'River I' and 'River II' puzzles on codingame.com. Used a `Set` to do some caching and optimise my solution.

**Thoughts** This was the first time where I really saw a use for JS' relatively new `Set` data structure. At first, my solution was doing alot of duplicate computation. I introduced a cache using `Set` and dramatically improved my solution's performance.

### Link(s) to work

1. [The River I](https://github.com/snowfrogdev/codingame/tree/master/the-river-i)
2. [The River II](https://github.com/snowfrogdev/codingame/tree/master/the-river-ii)

## Day 15: May 6, Monday

**Today's Progress**: Solved the 'Max Rect' puzzle on codingame.com. Ended up using the Hill Climbing algorithm I have been using on another project. Beats having to try to reason with 5 nested loops. Added WebWorker to demo of Macronutrients Optimiser.

**Thoughts** I really enjoy using these stochastic algorithms to solve problems. They are much more fun to code and use than pure brute force or mathematical algorithms. Why do all this hard worl to try to find the best answer when you can let the computer do the work and find a good enough answer. It's a very pragmatic way of solving problems.

### Link(s) to work

1. [Robbery Optimisation](https://github.com/snowfrogdev/codingame/tree/master/max-rect)
2. [Macronutrients Optimiser](https://github.com/snowfrogdev/macro-nutrients-optimizer)

## Day 14: May 5, Sunday

**Today's Progress**: Built a demo of a small 'app' that uses my Macro Nutrients Optimizer algorithm.

**Thoughts** Working in pure HTML and TS without a framework was eye opening. We often take for granted what front-end frameworks do for us. I wouldn't want to develop an entire app this way. Still, for very small throwaway projects like this, going vanilla makes sense.

### Link(s) to work

1. [Macronutrients Optimiser](https://github.com/snowfrogdev/macro-nutrients-optimizer)

## Day 13: May 4, Saturday

**Today's Progress**: Added early stopping to the Hill Climbing algorithm used in the Macronutrients optimizer. The algorithm will now stop if a certain time limit has been reached or if a result of a certain presicion has been reached. Also implemented a minimum weight for ingredients to avoid recipes where ingredients were set to 0 grams.

**Thoughts** The class is starting to get a little to be for my taste, I'm going to have to refactor soon as I keep adding functionality. I'm also going to have to implement some tests, didn't exactly develop this TDD style.

### Link(s) to work

1. [Macronutrients Optimiser](https://github.com/snowfrogdev/macro-nutrients-optimizer)

## Day 12: May 3, Friday

**Today's Progress**: Worked some more on the optimization problem submitted by [@DashBarkHuss](https://twitter.com/DashBarkHuss/status/1123733614108336128). I added the Random Restart meta-algorithm and am quite pleased with the results.

**Thoughts** Algorithms are so much fun. I can understand why people would want to work on games instead of web apps. I often feen like they are mostly about CRUD operations and very little interesting business logic. Tomorrow, I'll implement Stochastic Hill-Climbing instead of Steepest Ascent Hill Climbing, which is what I'm using at the moment, and see if it'll improve the results even more.

### Link(s) to work

1. [Macronutrients Optimiser](https://github.com/snowfrogdev/macro-nutrients-optimizer)

## Day 11: May 2, Thursday

**Today's Progress**: Worked on solving an optimization problem for [@DashBarkHuss](https://twitter.com/DashBarkHuss/status/1123733614108336128) and the ['Robbery Optimisation'](https://www.codingame.com/training/easy/robbery-optimisation) puzzle on codingame.com. Refreshed my understanding of the Hill Climbing algorithm.

**Thoughts** Both problems were a bit harder to solve than I initally thought. Sometimes you need to take a step back and really think things through. Watching me do a lot of thinking out loud and very little coding probably didn't make for the most interesting live coding session on Twitch.

### Link(s) to work

1. [Macronutrients Optimiser](https://github.com/snowfrogdev/macro-nutrients-optimizer)
2. [Robbery Optimisation](https://github.com/snowfrogdev/codingame/tree/master/robbery-optimisation)

## Day 10: May 1, Wednesday

**Today's Progress**: Worked through the 'Hamming', 'Scrabble Score' and 'Space Age' exercises on [exercism.io](https://exercism.io).

**Thoughts** 'Scrabble Score' was interesting. It was the first time I got to use a Map with keys of type Array.

### Link(s) to work

1. [Hamming](https://github.com/snowfrogdev/Exercism/tree/master/typescript/hamming)
2. [Scrabble Score](https://github.com/snowfrogdev/Exercism/tree/master/typescript/scrabble-score)
3. [Space Age](https://github.com/snowfrogdev/Exercism/tree/master/typescript/space-age)

## Day 9: April 30, Tuesday

**Today's Progress**: Finished the 'Allergies', 'Raindrops' and 'ETL' exercises on [exercism.io](https://exercism.io). Finished work on xmentor CLI.

**Thoughts** The 'Allergies' exercise was the first time I had to use a bitmask and bitwise operations. I'm glad I got to learn about it because I can see myself reaching for this in the future. Thanks to [gluegun](https://infinitered.github.io/gluegun/) I think making CLI tools has the dangerous potential of becoming like a drug to me.

### Link(s) to work

1. [Allergies](https://github.com/snowfrogdev/Exercism/blob/master/typescript/allergies/allergies.ts)
2. [Raindrops](https://github.com/snowfrogdev/Exercism/tree/master/typescript/raindrops)
3. [ETL](https://github.com/snowfrogdev/Exercism/tree/master/typescript/etl)
4. [xmentor](https://github.com/snowfrogdev/xmentor)

## Day 8: April 29, Monday

**Today's Progress**: Worked through the 'Protein translation', 'Nucleotide count' and started the 'Allergies' exercises on [exercism.io](https://exercism.io). Started working on a CLI to automatically download and run tests on student exercises on exercism.io. I call it xmentor for now.

**Thoughts** I had fun working on these relatively simple exercises. I ended learning about TS index signatures. Making CLI tools is a lot of fun. I just love automating stuff.

### Link(s) to work

1. [Protein translation](https://github.com/snowfrogdev/Exercism/blob/master/typescript/protein-translation/protein-translation.ts)
2. [Nucleotide count](https://github.com/snowfrogdev/Exercism/blob/master/typescript/nucleotide-count/nucleotide-count.ts)
3. [xmentor](https://github.com/snowfrogdev/xmentor)

## Day 7: April 28, Sunday

**Today's Progress**: Made a mockup of QTsum, a Quentin Tarantino themed placeholder text generator inspired by [Jeffsum](https://jeffsum.com/) and started writing the html and css.

**Thoughts** I need to get better at CSS. It's the only tech where I seem to have a hard time remembering what does what. There's just so many options.

### Link(s) to work

1. [QTsum mockup](https://www.figma.com/file/Bsq93tgHutCp8VSEvtI8Nyfy/QT-ipsum?node-id=0%3A1)
2. [QTsum repo](https://github.com/snowfrogdev/qtsum)

## Day 6: April 27, Saturday

**Today's Progress**: Refactored the `new` command in Vts-CLI's using the Chain of Responsibility pattern.

**Thoughts** Implementing the CoR pattern was fun and I learned a lot. Hesitated between CoR and Builder pattern. Time will tell if I made the right choice.

### Link(s) to work

1. [Vts - Vanilla TypeScript Starter](https://github.com/snowfrogdev/vts)

## Day 5: April 26, Friday

**Today's Progress**: Solved the LUMEN puzzle on [codingame.com](https://codingame.com). Refactored some of Vts-CLI's code.

**Thoughts** Got a little lazy with the refactoring, but all in all I'm pleased with the solution I have used for this puzzle. Recursion for the win!

### Link(s) to work

1. [Lumen](https://github.com/snowfrogdev/codingame/blob/master/lumen/src/main.ts)
2. [Vts - Vanilla TypeScript Starter](https://github.com/snowfrogdev/vts)

## Day 4: April 25, Thursday

**Today's Progress**: Started working on the LUMEN puzzle on [codingame.com](https://codingame.com). Pushed version 1.1.0 of Vts-CLI to NPM. Added the option to setup a web project using parcel as a bundler.

**Thoughts** Ran into some weird problems with the way Rollup seemed to output my TS code. Will have to look into that.

### Link(s) to work

1. [Lumen](https://github.com/snowfrogdev/codingame/blob/master/lumen/src/main.ts)
2. [Vts - Vanilla TypeScript Starter](https://github.com/snowfrogdev/vts)

## Day 3: April 24, Wednesday

**Today's Progress**: Solved the 'Ghost Legs' puzzle on [codingame.com](https://codingame.com). Polished my Vts CLI project and published it on NPM (vts-cli).

**Thoughts** An interesting puzzle to solze. It took me awhile to wrap my head around the problem space but once I figured a strategy to solve the problem it was relatively easy to solve. Spent almost 20 minutes refactoring afterwards to make it more readable.

I used [Gluegun](https://infinitered.github.io/gluegun/#/) to make the CLI tool and it was a real pleasure to use. Very easy to learn and quite powerful. I'm looking forward to automating alot of stuff with this little tool.

### Link(s) to work

1. [Ghost Legs](https://github.com/snowfrogdev/codingame/blob/master/ghost_legs/src/main.ts)
2. [Vts - Vanilla TypeScript Starter](https://github.com/snowfrogdev/vts)

## Day 2: April 23, Tuesday

**Today's Progress**: I've gone through the 'RNA Transcription' exercise on the Typescript track on [exercism.io](https://exercism.io). I've also worked on creating a small cli tool to generate Vanilla Typescript library starter code.

**Thoughts** The 'RNA Transcription' was a fun exercise. Though the problem was relatively easy to solve it gave me the opportunity to use some language features like `enum` and `type` that I haven't used much in the past.

I'm almost done with the first version of my cli tool. I'll add a bit of polish, refactor the code and then it'll be ready to publish to NPM.

### Link(s) to work

1. [RNA Transcription](https://github.com/snowfrogdev/Exercism/tree/master/typescript/rna-transcription)
2. [Vts - Vanilla TypeScript Starter](https://github.com/snowfrogdev/vts)

## Day 1: April 22, Monday

**Today's Progress**: I've gone through the 'reverse string', 'triangle' and 'collatz conjecture' exercises on the Typescript track on [exercism.io](https://exercism.io).

**Thoughts** It feels nice to start a new challenge that will get me coding everyday. The fact that I'm logging everything on Github and stream on Twitch is great for accountability.

### Link(s) to work

1. [Reverse String](https://github.com/snowfrogdev/Exercism/tree/master/typescript/reverse-string)
2. [Triangle](https://github.com/snowfrogdev/Exercism/tree/master/typescript/triangle)
3. [Collatz Conjecture](https://github.com/snowfrogdev/Exercism/tree/master/typescript/collatz-conjecture)
